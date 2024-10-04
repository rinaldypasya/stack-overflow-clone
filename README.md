
# Stack Overflow Clone 🚀

## Table of Contents

- [Stack Overflow Clone 🚀](#stack-overflow-clone-)
  - [Table of Contents](#table-of-contents)
  - [Technology Used](#technology-used)
  - [Features](#features)
  - [Top-level directory structure](#top-level-directory-structure)
  - [Screenshots of the project](#screenshots-of-the-project)
  - [Installation](#installation)
    - [Frontend](#frontend)
    - [Backend](#backend)

## Technology Used

| Technology | Features |
|------------|----------|
|   React.js      |  Frontend of the application |
| Redux | State Management|
| Node.js, Express.js    |  Backend of the application  |
|    MongoDB Atlas, Mongoose    | Database for the application|
| Bcrypt     |    Password Management      |
| JSON Web Token     |    Authorization and Authentication |
| Render     |     Deployment     |  
| Postman | API Testing, Debugging and Documentation |

## Features

Features of our Stack Overflow Clone are as follows:

- **Ask & Answer:** Post your coding questions and provide answers to help fellow developers.
- **Voting:** Upvote helpful questions and answers to recognize and encourage valuable contributions.
- **Tags & Categories:** Organize content by adding relevant tags and categories to questions.
- **Search:** Easily find answers using our powerful search functionality.
- **User Profiles:** Build your developer identity, showcase your skills, and keep track of your contributions.
- **Responsive Design:** Enjoy a seamless experience across devices, from desktop to mobile.

## Top-level directory structure

 ├── client                   # Frontend React.js directory
 │   ├── public              # Public assets for the React app (images, etc.)
 │   ├── src                 # React application source code
 │   │   ├── components      # Reusable UI components
 │   │   ├── pages           # Individual page components
 │   │   ├── App.js          # Root component
 │   │   ├── index.js        # Entry point for React app
 │   │   └── ...             # Other React-related files and folders
 ├── server                  # Backend Node.js/Express directory
 │   ├── controllers         # Controllers for handling requests
 │   ├── models              # Database models and schemas
 │   ├── routes              # API route handlers
 │   ├── utils               # Utility files
 │   ├── views               # Templates for rendering server-side views
 │   ├── app.js              # Express app setup
 │   ├── package-lock.json   # Node.js package lock
 │   └── package.json        # Node.js package information
 ├── .gitignore
 └── README.md

<div align="center">
<img src="https://shorturl.at/9t2Se" alt="mvc architecture" height="400"/>
</div>
<br/>

## Screenshots of the project

<table>
  <tr>
    <td>Home Page</td>
    <td>Tags Page</td>
  </tr>
  <tr>
    <td>
   <img src="https://shorturl.at/lb2V3" border="0">
    </td>
        <td>
<img src="https://shorturl.at/uajd6" border="0"></td>

  </tr>
</table>
<table>
  <tr>
    <td>SignUp Page</td>
    <td>Login Page</td>
  </tr>
  <tr>
    <td>
<img src="https://shorturl.at/ReXsI" border="0"></td>
<td><img src="https://shorturl.at/IfIS3" alt="screely-1677925542185" border="0">
</td>
  </tr>
</table>

## Installation

To setup the project on your local environment, follow the given steps:

Clone the repository

```bash
  git clone {repo_url}
```

### Frontend

Move to the client directory

```bash
  cd client
```

Install the necessary dependencies

```bash
  npm install
```

To start the server in development mode

```bash
  npm start
```

Go to `http://localhost:3000` to view the website.

### Backend

Move to the server directory

```bash
  cd server
```

Install the necessary dependencies

```bash
  npm install
```

Add a config.env file in the root directory and enter your MongoDb Atlas and JWT Secret key
The format of .env file should be similar to the following

```bash
CONNECTION_URL = "MONGO DB URL"
JWT_SECRET = "testjwtsecret"
```

To start the server in development mode

```bash
  npm start
```

Server will start at `http://localhost:5000`
