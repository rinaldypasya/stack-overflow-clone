
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

```bash
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
```

![mvp](https://github.com/user-attachments/assets/c476a63c-cb22-45c1-a6f6-5d1f566afeb4)



## Screenshots of the project

<table>
  <tr>
    <td>Home Page</td>
    <td>Tags Page</td>
  </tr>
  <tr>
    <td>
   <img src="https://i.ibb.co/gM7xXWr/screely-1692895310281.png" border="0">
    </td>
        <td>
<img src="https://i.ibb.co/t2mPvSw/screely-1692895676919.png" alt="screely-1677925947288" border="0"></td>

  </tr>
</table>
<table>
  <tr>
    <td>SignUp Page</td>
    <td>Login Page</td>
  </tr>
  <tr>
    <td>
<img src="https://i.ibb.co/vd9TjxS/screely-1692895003181.png" alt="screely-1677924790571" border="0"></td>
<td><img src="https://i.ibb.co/nc7vgn1/screely-1692894712324.png" alt="screely-1677925542185" border="0">
</td>
  </tr>
</table>
<table>
  <tr>
    <td>Question Detail Screen</td>
    <td>Posting an Answer Screen</td>
  </tr>
  <tr>
    <td>
<img src="https://i.ibb.co/M1n4dHf/screely-1692897031364.png" alt="screely-1677925947288" border="0"></td>
<td>
   <img src="https://i.ibb.co/TmSPn3k/screely-1692897192656.png" border="0">
    </td>
  </tr>
</table>
<table>
  <tr>
    <td>All Users Screen</td>
    <td>Ask a Question Screen</td>
  </tr>
  <tr>
<td>
   <img src="https://i.ibb.co/Bym2PSg/screely-1692896520603.png" border="0">
    </td>
<td>
   <img src="https://i.ibb.co/YB4VDgq/screely-1692896859187.png" border="0">
    </td>

  </tr>
</table>
<table>
  <tr>
    <td>User Profile Screen</td>
    <td>Other User's Profile Page</td>
  </tr>
  <tr>
     <td>
<img src="https://i.ibb.co/3kPJWtS/screely-1692895544650.png" border="0"></td>
    <td>
<img src="https://i.ibb.co/LRv0rQh/screely-1692896637899.png" alt="screely-1677925947288" border="0"></td>
  </tr>
</table>

## Installation

To setup the project on your local environment, follow the given steps:

Clone the repository

```bash
  git clone https://github.com/rinaldypasya/stack-overflow-clone.git
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
