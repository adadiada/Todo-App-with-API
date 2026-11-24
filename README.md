# React Todo App

A modern, responsive task management web application that allows users to create, edit, filter, and organize their daily tasks. Built with React and TypeScript, the app syncs task states with a REST API and provides real-time feedback for all user actions.

## Live Preview

- [DEMO LINK](https://adadiada.github.io/Todo-App-with-API/)

## Technologies Used

- **React** — component-based UI architecture and custom hooks
- **TypeScript** — strict static typing for safer and more maintainable code
- **Bulma / SCSS** — clean, responsive styling and UI components
- **Fetch API / REST API** — asynchronous data loading, creation, updating, and deletion of todos
- **Vite** — fast project bundling and local development server

## Getting Started

Follow these instructions to set up and run the project locally on your machine:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/adadiada/Todo-App-with-API
   cd your-todo-repo-name
   ```

2. **Install dependencies:**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the project locally:**

   ```bash
   npm start
   # or
   yarn start
   ```

## Features

- **Full CRUD Operations:** Add new tasks, toggle completion status, rename existing todos via double-click, and delete tasks.
- **Bulk Actions:** Toggle all tasks at once or clear all completed items with a single click.
- **Smart Filtering:** Filter tasks dynamically by **All**, **Active**, and **Completed** statuses with a live counter of remaining items.
- **Error Handling & Loaders:** Visual loading indicators during API requests and clear error notifications if an operation fails.
