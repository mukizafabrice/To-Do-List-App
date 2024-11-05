
 To-Do List App

A simple and user-friendly to-do list application built withreact js, tailwindcss, Node.js, Express, MongoDB, and Mongoose. This app allows users to create, view, update, and delete tasks, helping them stay organized and manage their daily activities.

 Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [License](#license)

---

 Features

- Add New Tasks: Create tasks with a description, optional due date, and priority.
- View Tasks: Display a list of all tasks with filtering and sorting options.
- Update Tasks: Edit task details as needed.
- Complete Tasks: Mark tasks as completed.
- Delete Tasks: Remove tasks you no longer need.

 Getting Started

These instructions will help you set up a local development environment for the to-do list app.

 Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (either locally or through MongoDB Atlas)
- [Git](https://git-scm.com/)

 Installation

1. Clone the repository**:

    ```bash
    git clone https://github.com/mukizafabrice/todo-list-app.git
    cd todo-list-app
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up environment variables:

   Create a `.env` file in the root directory and add your MongoDB URI:

   ```plaintext
   MONGODB_URI=mongodb://localhost:27017/todoapp
   PORT=3000
   ```

4. Start the server:

    ```bash
    npm start
    ```

   The app should now be running on `http://localhost:3000`.

## Usage

1. Add Tasks: Use the provided form or API endpoint to add new tasks.
2. View and Manage Tasks: You can view tasks, mark them as complete, update them, or delete them.
3. Filter/Sort Tasks: Apply different filters or sorting options to organize tasks as per your preferences.

## API Endpoints

Here are the main API endpoints for the to-do list app:

- `GET /tasks`: Get all tasks
- `POST /tasks`: Add a new task
- `PUT /tasks/:id`: Update a task by ID
- `PATCH /tasks/:id/complete`: Mark a task as completed
- `DELETE /tasks/:id`: Delete a task by ID

### Example Request

#### Add a New Task

```http
POST /tasks
Content-Type: application/json

{
  "description": "Finish homework",
  "dueDate": "2024-11-10"
}
```

ark Task as Complete

* Technologies Used
-react js
- Node.js- JavaScript runtime environment
- Express - Web application framework for Node.js
- MongoDB - NoSQL database
- Mongoose - ODM library for MongoDB and Node.js
- Dotenv - For environment variable management



