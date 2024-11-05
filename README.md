Here is the live preview of this project

[Live Preview](https://utkarsh-todo-anand.netlify.app)

# ToDo List

## Overview

**ToDo List** is a simple and intuitive task management application built using **React.js**. This project demonstrates the core features of a modern front-end application, focusing on state management, component-based architecture, and user interaction. The app allows users to create, view, update, and delete tasks, helping them organize their daily activities efficiently.

## Features

- **Add Tasks**: Users can add new tasks with a title and optional description.
- **View Tasks**: All tasks are displayed in a list with their current status (completed or pending).
- **Update Tasks**: Tasks can be edited to change the title or description.
- **Delete Tasks**: Unwanted tasks can be removed permanently.
- **Mark as Completed**: Users can mark tasks as completed, and toggle them back to pending if needed.
- **Filter Tasks**: Option to filter tasks based on their completion status (All, Completed, Pending).
- **Responsive Design**: The application is fully responsive and works seamlessly on desktop, tablet, and mobile devices.

## Technologies Used

- **React.js**: Core library for building the user interface.
- **React Hooks**: Used for managing component state and side effects.
- **CSS Modules**: For styling individual components, promoting reusability and maintainability.
- **Local Storage**: To persist tasks between sessions.
- **ES6+**: Utilized modern JavaScript features for cleaner and more efficient code.

## Installation and Setup

To get the ToDo List project up and running on your local machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/todo-list.git
   cd todo-list
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the application:**
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:3000/`.

## Project Structure

```
todo-list/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── TaskItem.js
│   │   ├── TaskList.js
│   │   ├── TaskForm.js
│   │   └── Filter.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

## How It Works

1. **State Management**: The application uses React's `useState` hook to manage the list of tasks and their states.
2. **Task Operations**: 
   - Adding a task updates the state with a new task object.
   - Editing a task modifies the corresponding object in the state.
   - Deleting a task filters it out from the state.
3. **Persistence**: The tasks are saved to the browser's local storage, ensuring data persists across page reloads.
4. **Conditional Rendering**: Based on the task's status, different UI elements are rendered to indicate whether a task is completed or pending.

## Future Enhancements

- **Due Dates**: Allow users to set and view due dates for tasks.
- **Priority Levels**: Introduce task prioritization (e.g., High, Medium, Low).
- **User Authentication**: Enable users to create accounts and save their tasks in a cloud-based database.
- **Dark Mode**: Implement a toggle for dark mode to enhance user experience.

## Contribution

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. Ensure that your code follows the project's coding standards.

