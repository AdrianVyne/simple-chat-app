# React Node Chat App

This is a chat application built with React and Node.js.

## Getting Started

To get the application up and running locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `backend` folder and create a `.env` file with the following variables:
   PORT=5000
   MONGODB_URI=<your MongoDB URI>
   JWT_SECRET=<your JWT secret>

Make sure to replace `<your MongoDB URI>` and `<your JWT secret>` with your own values.

3. Run `npm install` to install the dependencies for the backend.
4. Run `npm start` to start the backend server.

5. Navigate to the `frontend` folder and create a `.env` file with the following variables:
   REACT_APP_API_URL=http://localhost:5000

Make sure the value of `REACT_APP_API_URL` matches the port number specified in the `PORT` variable in the `.env` file for the backend.

6. Run `npm install` to install the dependencies for the frontend.
7. Run `npm start` to start the frontend server.

8. Open a browser and go to `http://localhost:3000` to use the application.
