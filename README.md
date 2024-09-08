# TodoMatic - A ReactJS Todo App

## Project Overview
TodoMatic is a simple and efficient Todo app built with ReactJS. It allows users to add, edit, delete, and filter tasks based on their status (Active, Completed, All). The app leverages React hooks for state management and provides an intuitive and accessible user interface.

## Features
- **Add Tasks**: Easily add new tasks to your todo list.
- **Edit Tasks**: Modify existing tasks with a smooth editing interface.
- **Delete Tasks**: Remove tasks from the list with a single click.
- **Task Completion**: Mark tasks as completed or uncompleted.
- **Filter Tasks**: View tasks based on their status (All, Active, Completed).
- **Accessibility**: Full support for keyboard navigation and screen readers.

## Technology Stack
- **ReactJS**: Frontend framework used for building dynamic user interfaces.
- **Nanoid**: Library for generating unique task IDs.
- **CSS**: Custom styling for the app interface.

## Installation & Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/rahul-charaki/react-todo-app
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

5. Open the app in your browser at `http://localhost:3000`.

## Project Structure
- `components/`: Contains all the reusable components such as Form, FilterButton, and Todo.
- `App.js`: Main component that holds the state and logic for the entire app.
- `index.js`: Entry point of the React application.

## Future Enhancements
- Add form validation to prevent empty task submissions.
- Implement task persistence using local storage or a backend API.
- Add more customization options such as due dates and priority levels.
