Todo List Application

This project is a simple console-based Todo List application built using HTML and JavaScript. It allows users to create, list, and delete todos directly from their browser's prompt.

Table of Contents

Installation


Usage


File Structure

Code Explanation

Features

License

Installation

Clone the repository or download the files:



git clone https://github.com/your-repo/todo-list-app.git

Navigate to the project folder:


cd todo-list-app

Open the index.html file in your browser:


open index.html

Usage

"new": Adds a new todo to the list.

"list": Displays all current todos with their index.

"delete": Removes a todo based on the provided index.

"quit" or "q": Exits the application.

The application runs in a loop, repeatedly asking the user what action they want to take (add, list, or delete a todo) until the user types 'quit' or 'q' to exit.

Example Flow

The user is prompted to enter a command.

If they type 'list', all todos will be displayed.

If they type 'new', they will be prompted to enter a new todo item.

If they type 'delete', they will be prompted to provide the index of the todo they wish to remove.

Typing 'quit' or 'q' will exit the app.

File Structure
plaintext

todo-list-app/
│
├── index.html      # Main HTML file containing instructions for the todo app
└── todo.js         # JavaScript file containing logic for managing todos
Code Explanation
index.html: The HTML file that provides basic instructions for using the app. It also links to the JavaScript file (todo.js).

html

<h1>Todo List</h1>

<ul>
  
    <li>"new" - Add a Todo</li>
    
    <li>"list" - List All Todos</li>
    
    <li>"delete" - Remove Specific Todo</li>
    
    <li>"quit" - Quit App</li>
    
</ul>

todo.js: Contains the JavaScript logic that prompts the user for input and manages the todo list.

javascript

const todos = ['Collect Chicken Eggs', 'Clean Litter Box'];

while (input !== 'quit' && input !== 'q') {

    // handle commands: list, new, delete
}

Features

Simple and easy-to-use console-based interface.

Add, view, and remove todos from a dynamically managed list.

Loop functionality keeps the app running until the user chooses to quit.

License

This project is open source and available under the MIT License.
