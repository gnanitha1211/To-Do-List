# MERN Stack To-Do List App

## Overview

This is a To-Do List application built using the MERN stack: MongoDB, Express.js, React.js, and Node.js. The app provides basic CRUD (Create, Read, Update, Delete) functionalities to manage tasks. The front-end is styled using Tailwind CSS and state management is handled with Redux.

## Features

- **CRUD Operations**: Create, read, update, and delete tasks.
- **Responsive Design**: The user interface is responsive and adapts to various devices.
- **State Management**: Redux is used for managing the application state efficiently.

## Technologies

- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (via Mongoose)

- **Frontend**:
  - React.js
  - Redux.js
  - Tailwind CSS

## Setup

### Prerequisites

Ensure you have the following installed:

- Node.js and npm
- MongoDB

### Backend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mern-todo-app.git
   ```

2. Navigate to the backend directory:
   ```bash
   cd mern-todo-app/backend
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file in the `backend` directory and add your MongoDB connection string:
   ```
   MONGO_URI=your_mongodb_connection_string
   ```

5. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

## Usage

- **Access the App**: Open your browser and go to `http://localhost:3000` to view the application.
- **Managing Tasks**: Use the provided UI to create, read, update, and delete tasks.

## API Endpoints

- **GET /api/tasks**: Retrieve all tasks.
- **POST /api/tasks**: Create a new task.
- **PUT /api/tasks/:id**: Update an existing task.
- **DELETE /api/tasks/:id**: Delete a task.

## Contributing

Contributions are welcome! If you find any issues or want to improve the project, feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React.js](https://reactjs.org/)
- [Redux.js](https://redux.js.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
