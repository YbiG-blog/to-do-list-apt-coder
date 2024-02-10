## Project Setup

Before you start the project, make sure you have the necessary dependencies installed. You can use npm for managing packages.

1. Install project dependencies:
   ```
   npm install
   ```

2. Start the development server:
   ```
   npm start
   ```
3. Start Json-Server ( PORT - 8000 ):
   ```
   json-server --watch config/db.json --port 8000
 
   ```  

By default, the frontend runs on port 3000. You can access the web application in your browser at `http://localhost:3000`.

The backend ( json server ) runs on port 8000. You can access the web application in your browser at `http://localhost:8000/toDoList`.

## Technologies Used

- React
- Axios (for making API requests)
- CSS (for styling)
- Json-Server

- `GET    /toDoList`: Get the list of tasks.
- `POST   /toDoList`: Add a new task.
- `PUT    /toDoList/:_id(taskId)`: Mark a task as completed.
- `PUT    /toDoList/:_id(taskId)`: Edit Task.
- `DEL    /toDoList/:_id((taskId))`: Delete a task.

