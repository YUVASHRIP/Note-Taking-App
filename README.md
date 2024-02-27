# Note-Taking-App
# MERN Stack Note-Taking App

A simple Note-Taking application built using the MERN stack (MongoDB, Express.js, React, Node.js). This application allows users to create, edit, and delete notes. Basic user authentication is implemented to ensure that users can securely save and access their own notes.

## Features

- User Registration: Users can create an account to start using the note-taking app(new user).
- User Login: Registered users can log in to access their notes(Existing users login).
- Note Creation: Users can create new notes with a title and content.
- Note Editing: Edit existing notes to update their title or content.
- Note Deletion: Delete unwanted notes.
- User Authentication: Implemented basic user authentication to secure user-specific notes.

## Prerequisites
- Node.js and npm install.
- MongoDB Atlas account for database storage.

## 1.Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
# Install backend dependencies(server)
    cd backend
    npm install
# Install frontend dependencies(client)
    cd ../client
    npm install

## 2.Set up MongoDB:
- Create a MongoDB Atlas account and obtain the connection string.
- Update the YOUR_MONGODB_CONNECTION_STRING in backend/server.js with your connection string.

## 3.Run the application:
    npm run dev

## Usage
 - Register a new user or log in if you already have an account.
 - Create, edit, and delete notes.
 - Logout to securely end your session.

## Technology Stack
## Backend:
- Node.js
- Express.js
- MongoDB (MongoDB Atlas)
- JSON Web Tokens (JWT) for authentication
## Frontend:
- React
- Axios for API communication

## Folder Structure
- server/: Backend server code.
- client/: Frontend React app code.

## Contributing
If you'd like to contribute, please fork the repository and create a new branch. Pull requests are welcome!
