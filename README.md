# Note Taker

## Description

Note Taker is a web application that allows users to create, save, and manage notes. It provides a simple and convenient way for users to jot down and store their thoughts, ideas, and reminders.

## Technologies Used

- Express: A web application framework for Node.js, used to handle routing and server-side logic.

## Project Structure

- `db`: Contains a `db.json` file, which is used to store the notes created by users.
- `public`: Contains an `assets` directory, which further contains a `css` directory and a `js` directory. The `css` directory contains a `styles.css` file, which is used to style the web pages. The `js` directory contains an `index.js` file, which contains the client-side JavaScript code for the application. The `public` directory also contains an `index.html` file, which serves as the homepage of the application, and a `notes.html` file, which is used to display and manage the notes.
- `routes`: Contains an `index.js` file, which defines the routes for the application.
- `server.js`: The main entry point of the application. It sets up the Express server, configures the routes, and starts the server.

## Installation

1. Clone the repository: `git clone https://github.com/Krich2022/take-my-notes.git`
2. Navigate to the project directory: `cd take-my-notes`
3. Install dependencies: `npm install`
4. Start the server: `node server.js`

## Usage

Once the server is running, open a web browser and navigate to `http://localhost:3000`. From there, you can create, view, update, and delete notes.

## Deployment

The application is deployed on Heroku and can be accessed at [https://take-my-notes-38580e0031a0.herokuapp.com/](https://take-my-notes-38580e0031a0.herokuapp.com/).
