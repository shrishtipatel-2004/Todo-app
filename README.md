# Task Manager API

A simple yet powerful task management application built with Node.js and Express.js, featuring a web-based UI and file-based persistence.

## Features

- Create new tasks
- View all tasks
- Mark tasks as complete/incomplete
- Delete tasks
- Persistent storage using JSON file
- Responsive web UI with EJS templates
- RESTful API endpoints

## Tech Stack

- Backend: Node.js, Express.js
- Frontend: EJS (Embedded JavaScript Templating)
- Data Storage: JSON file-based persistence
- Server Port: 3000

## Installation

1. Install dependencies:
```bash
npm install
```

## Running the Application

Start the server:
```bash
npm start
```

Or directly with Node:
```bash
node app.js
```

The application will start on http://localhost:3000

## API Endpoints

- GET / - Display all tasks
- POST /add - Add a new task
- POST /complete/:id - Mark a task as complete
- POST /delete/:id - Delete a task

## Usage

1. Open your browser and navigate to http://localhost:3000
2. Enter a task title in the input field
3. Click "Add Task" to create a new task
4. Click the checkbox to mark tasks as complete
5. Click "Delete" to remove a task

## Data Persistence

All tasks are automatically saved to tasks.json file. Data persists between server restarts.

## License

ISC
successfully created README.md
successfully created .gitignore