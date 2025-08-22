# Full Stack Registration Form Project

## Overview

This project is a full-stack web application that implements a user registration form. The application is built using HTML, CSS, Node.js, Express.js, and MongoDB. The goal is to create a seamless and secure user registration process, storing user information in a MongoDB database.

## Technologies Used

- **HTML and CSS**: The front end of the application is built with HTML for structuring the web pages and CSS for styling.

- **Node.js**: The server-side logic is implemented using Node.js, providing a JavaScript runtime environment.

- **Express.js**: Express.js is used as the web application framework for Node.js, simplifying the process of handling HTTP requests and responses.

- **MongoDB**: MongoDB is employed as the database system for storing user registration data. It offers a flexible and scalable NoSQL database solution.

## Tools and Libraries

- **[Express Validator](https://express-validator.github.io/docs/)**: Used for validating and sanitizing user input on the server-side.

- **[Mongoose](https://mongoosejs.com/)**: A MongoDB object modeling tool for Node.js, used for interacting with the MongoDB database in an easier way.

- **[dotenv](https://www.npmjs.com/package/dotenv)**: A zero-dependency module that loads environment variables from a `.env` file into `process.env`.

## Features

1. **User Registration Form**: The application provides a user-friendly registration form where users can enter their information.

2. **Validation**: Client-side and server-side validation mechanisms ensure that the entered data is accurate and secure.

3. **Database Storage**: User registration details are securely stored in a MongoDB database, allowing for efficient retrieval and management.

## Getting Started

   
1.**Install dependencies**: 

 --> cd registration-form
   
 --> npm install

2.**Configure MongoDB connection**:

 --> Create a .env file in the root directory.

 --> Add your MongoDB connection string as MONGODB_URI.

3.**start the application**:

 --> npm start

