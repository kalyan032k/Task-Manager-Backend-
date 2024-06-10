# Task Manager
A simple Task Manager application that allows users to perform CRUD operations (Create, Read, Update, Delete) using Node.js, Express, JavaScript, MongoDB, and Postman.

### Introduction
This project is a Task Manager application designed to help users manage their tasks efficiently. It provides a RESTful API to perform CRUD operations on tasks, allowing users to create new tasks, read existing tasks, update tasks, and delete tasks.

### Features
Create a new task
Retrieve all tasks
Retrieve a single task by ID
Update an existing task
Delete a task

### Technologies and tools
Node.js
Express
MongoDB
Mongoose
JavaScript
Postman

### Installation
Clone the repository:

git clone https://github.com/your-username/task-manager.git
cd task-manager

### Install dependencies:

npm install

### Set up your MongoDB connection:
Create a .env file in the root directory.
Add your MongoDB connection string to the .env file

MONGODB_URI=your-mongodb-connection-string

### Start the server:
npm start


### Usage
Create a new task: Use the POST /api/tasks endpoint with the required task details.

Retrieve all tasks: Use the GET /api/tasks endpoint to get a list of all tasks.

Retrieve a single task: Use the GET /api/tasks/:id endpoint to get details of a specific task.

Update a task: Use the PATCH /api/tasks/:id endpoint to update task details.

Delete a task: Use the DELETE /api/tasks/:id endpoint to remove a task.

Use Postman to test the API endpoints. Make sure your server is running before making requests.



