## Project Overview

This project sets up a Node.js server using Express, integrates Mongoose for MongoDB interaction, and follows a structured approach for handling User data through CRUD operations.

## Installation and Setup

1.  Start a new Node.js project:
    npm init --y
2.  Install Dependencies:
    npm install express mongoose dotenv nodemon
3.  Configure environment variable in /config/.env:
    MONGO_URI=mongodb://localhost:27017/your-database-name
    PORT=3000

## Database Connections

The server is configured to connect to the MongoDB database using the connection string provided in the .env file.

## User Model

In the models folder, create a User.js file:

## Routes

Four routes are defined in server.js to handle CRUD operations:

1. GET: /users: Returns all users.
2. POST: /users: Adds a new user to the database.
3. PUT: /users/:id: Edits a user by ID.
4. DELETE: /users/:id: Removes a user by ID.

In each route callback function, Mongoose methods are used to manipulate data and return responses.
# restAPI-checkpoint
