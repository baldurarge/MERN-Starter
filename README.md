This is a starter package for a [Mongodb](https://www.mongodb.com), [Express](https://expressjs.com), [React](https://reactjs.org), [Node.js](https://nodejs.org/en/)

This project is a simple, Register/login/logout user, With simple validation. The React application is built with Redux, in order to have the user data available, throughout the application.

## Before starting

You need to install dependencies:

#### Server

in the root directory, run `npm install`.

#### Server

in the /client directory, run `npm install`.

You also need to add the mongodb connection.
in the root directory run `cd config && touch keys.js`

Then add this code to the file
`module.exports = { mongoURI: "mongodb+srv://<username>:<password>@cluster0-uqbre.mongodb.net/test?retryWrites=true" secretOrKey: "secret"};`

Replacethe `<username>` and `<password>` with the once you created at [Mongodb](https://www.mongodb.com)

## Start the server

In the project root directory, you can run:

### `npm server`

Runs the server in development mode, using nodemon.<br>
The server runs on [http://localhost:5000](http://localhost:5000).

The server will reload if you make edits.<br>
You will also see any lint errors in the console.

## Start the application

In the project /client directory, you can run:

### `npm start`

Runs the react application in development mode<br>
The application runs on [http://localhost:3000](http://localhost:3000).

The application will reload if you make edits.<br>
You will also see any lint errors in the console.
