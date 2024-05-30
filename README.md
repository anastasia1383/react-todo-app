# React Todo App with API


## Introduction
Welcome to the React Todo App with API! This application is designed to help you manage your tasks effectively. It allows you to add, delete, toggle the completion status, and rename todos, all while integrating with an external API to ensure your data is consistently up-to-date.
- [DEMO](https://anastasia1383.github.io/react-todo-app/)

## Technologies Used
1. React
2. TypeScript
3. Bulma
4. React Router

## Features
1. **Add Todos**: Easily add new todos to your list.
2. **Delete Todos**: Remove todos that are no longer needed.
3. **Toggle Todo Status**: Mark todos as completed or incomplete.
4. **Rename Todos**: Edit the titles of your todos to keep them relevant.

## Installation and Setup

### Prerequisites
- Node.js (v14.18.2) and npm installed on your machine
- React development environment set up

### Installation Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/react-todo-app.git

2. Navigate to the project directory:
   ```sh
   cd react-todo-app

3. Install the dependencies:
   ```sh
   npm install
   
## Running the Application
To start the application, run:
    
    npm start

## Functionality

### Adding a Todo
1. **Enter** the todo title in the input field.
2. **Press Enter** or click the **"Add" button** to add the todo to the list.

### Deleting a Todo
1. **Click the `x` button** next to the todo you want to delete.
2. The todo will be **removed from the list** upon successful API response.

### Toggling Todo Status
1. **Click on the checkbox** next to a todo to mark it as completed or incomplete.
2. The status will be **updated upon successful API response**.

### Toggle All Todos
1. **Click the "Toggle All" checkbox** to change the status of all todos at once.
2. If all todos are completed, clicking this will **mark them as incomplete** and vice versa.

### Renaming a Todo
1. **Double-click on the title** of the todo you wish to rename.
2. An **edit form will appear** in place of the title.
3. **Modify the title** and **press Enter** to save or click outside the input field to **save on blur**.
4. **Press `Esc`** to cancel the edit.
5. If the title is empty, the todo will be **deleted**.

