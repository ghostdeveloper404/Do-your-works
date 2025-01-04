
# Todo App

This is a simple Todo App built using ReactJS, VueJS, and TailwindCSS. The app uses LocalStorage to persist data, so your tasks will be saved even if you refresh the page.

## Features

- Add, edit, and delete tasks
- Mark tasks as completed
- Filter tasks by status (all, active, completed)
- Persistent storage using LocalStorage

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd todo-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. Open the app in your browser:
   ```bash
   http://localhost:3000
   ```
2. Start adding tasks by typing in the input field and pressing "Enter".
3. Use the buttons next to each task to mark it as completed or delete it.
4. Use the filter buttons to view all tasks, only active tasks, or only completed tasks.

## Contributing

We welcome contributions from the community. If you're new to open-source, here’s a great first issue to tackle:

### Issue: Fix the Task Deletion Bug

#### Description

There is a known issue where deleting a task doesn't always update the task list correctly. Sometimes the task appears to be deleted but reappears after a page refresh.

#### Steps to Reproduce

1. Add a few tasks.
2. Delete a task.
3. Refresh the page.
4. Observe that the deleted task reappears.

#### Possible Solution

The issue likely lies in the way tasks are being updated in LocalStorage. A fresh pair of eyes might catch the bug!

Feel free to fork the repository, make your changes, and submit a pull request. Please include a detailed explanation of the changes and the steps to test them.


# React + Vite


This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
