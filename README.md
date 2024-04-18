# To-Do List Application

## Overview
This To-Do List application is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with bcrypt.js for secure user authentication. It allows users to manage their daily tasks efficiently with a user-friendly interface.

## Features
- User authentication (login and signup).
- Add, delete, and mark tasks as completed.
- Tasks are saved in MongoDB for persistence.
- Responsive design for desktop and mobile devices.

## Prerequisites
Before you begin, ensure you have the following installed on your system:
- Node.js (v14 or later)
- npm (Node Package Manager)
- MongoDB (Local or MongoDB Atlas)

## Installation
To set up the To-Do List application on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/todo-list-mern.git
   cd todo-list-mern
   ```

2. **Install backend dependencies:**
   ```bash
   cd backend
   npm install
   ```

3. **Install frontend dependencies:**
   ```bash
   cd ../src
   npm install
   ```

## Running the Application
1. **Start the MongoDB service** (skip this step if using MongoDB Atlas).

2. **Run the backend server:**
   ```bash
   cd ../backend
   npm start
   ```

3. **Run the React frontend:**
   ```bash
   cd ../src
   npm start
   ```
   This should open the application in your default web browser. If it doesn't, visit [http://localhost:3000](http://localhost:3000).

## Usage
- **Register a new user or log in** to access your personal To-Do list.
- **Add tasks** by entering text into the input field and pressing "Enter" or clicking the add button.
- **Delete tasks** by clicking the delete button next to each task.
- **Mark tasks as complete** by clicking on the task text.

## Contributing
Contributions are welcome! Please feel free to fork this repository, make changes, and submit pull requests. You can also open issues for bugs, features, or other discussions.

## License
This project is licensed under the MIT License - see the [LICENSE]
