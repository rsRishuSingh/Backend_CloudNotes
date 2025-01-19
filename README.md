# Notes App API

This is a backend API for a Notes application built using **Express.js**, **MongoDB**, **JWT Authentication**, **Bcrypt** for password hashing, and **Mongoose** for database interaction. The application allows users to register, log in, manage their notes (create, fetch, update, delete), and store their information securely.
This project has been deployed via (https://render.com/)
## Features

- **User Registration**: Allows new users to create an account with a validated email and password.
- **User Login**: Allows users to log in with their credentials and obtain a JWT token for authentication.
- **Notes Management**: Users can create, update, fetch, and delete notes securely.
- **Authentication**: Uses JWT for securely handling authentication of requests.
- **Validation**: Requests for user registration, login, and note management are validated using `express-validator`.

## Technologies Used

- **Express.js**: Web framework for Node.js
- **MongoDB**: NoSQL Database for storing user and notes data.
- **Mongoose**: ODM for MongoDB in Node.js
- **JWT (JSON Web Tokens)**: For authentication and authorization
- **Bcrypt**: For password hashing and comparison
- **dotenv**: For managing environment variables
- **express-validator**: For request validation

# Express.js API for User Authentication and Notes Management

This is a simple Express.js API that handles user authentication (registration and login) and notes management. It provides functionality for registering a new user, logging in, fetching user details, adding notes, updating notes, deleting notes, and fetching notes for the logged-in user.


## Table of Contents

- [Installation](#installation)
- [Environment Setup](#environment-setup)
- [API Routes](#api-routes)
  - [User Routes](#user-routes)
    - [POST /createaccount](#post-createaccount)
    - [POST /login](#post-login)
    - [POST /getuser](#post-getuser)
  - [Notes Routes](#notes-routes)
    - [GET /fetchnotes](#get-fetchnotes)
    - [POST /addnote](#post-addnote)
    - [PUT /updatenote/:id](#put-updatenoteid)
    - [DELETE /deletenote/:id](#delete-deletenoteid)
- [Dependencies](#dependencies)
- [License](#license)
