# Notes Application

A full-stack Notes Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with JWT authentication and Tailwind CSS for styling. The application allows users to register, log in, and manage their notes with features like pinning and tagging.

## Features

- **User Authentication**: Secure user registration and login using JWT authentication.
- **CRUD Operations**: Users can create, read, update, and delete their notes.
- **Pin Notes**: Users can pin important notes for quick access.
- **Tagging**: Add tags to notes for better organization.
- **Responsive Design**: The application is responsive and works well on all devices.

## Live Demo

Check out the live version of the project: https://keen-melomakarona-08f738.netlify.app

## Technologies Used

- **Frontend**:
  - React.js
  - Tailwind CSS
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB
- **Authentication**:
  - JSON Web Tokens (JWT)
  
## Setup and Installation

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RajMogare/Notes-App.git
   
2. **Install Dependencies for backend:**
   ```bash
     cd backend
     npm install

3. **Install Dependencies for frontend:**
   ```bash
    cd frontend
    npm install

4. **Set up environment variables:**
     Create a .env file in the backend directory with the following:
    ```bash
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret

5. **Run the application For Frontend:**
     ```bash
     npm run dev

6. **Run the application For Backend:**
     ```bash
     npm start


