# Sign Up Process using React, Express.js, REST API and MongoDB

## Description

This project implements a Sign Up process using React.js for the frontend, Express.js and REST API for the backend, and MongoDB for storing user details.

## Technologies Used

- React.js
- Express.js
- REST API
- MongoDB
- Mongoose
- Node.js
- CSS

## Project Structure

```text
signup-react-express-mongodb
├── client
│   └── React frontend
├── server
│   ├── models
│   │   └── User.js
│   └── server.js
├── .gitignore


Features
- Sign Up form using React
- Email and password input
- REST API for Sign Up
- Express.js backend
- MongoDB database connection
- User data stored in MongoDB
- Duplicate email checking
- Form validation
API Endpoint
POST /api/signup
URL:
http://localhost:5000/api/signup

Request body:
{
  "email": "disha@example.com",
  "password": "123456"
}

How to Run
Backend
Open PowerShell in the server folder and run:
node server.js

The server runs on:
http://localhost:5000

Frontend
Open another PowerShell terminal in the client folder and run:
npm run dev

The React application runs on the Vite URL shown in the terminal.
Testing
The Sign Up REST API was tested using Postman.

The React Sign Up form was also tested by submitting user details through the frontend.
Database
MongoDB database:
signupDB

Collection:
users


Then press:

**Ctrl + S**

### Your root folder should now contain

```text
signup-react-express-mongodb
├── .gitignore
├── README.md
├── client
└── server