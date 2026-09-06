# to-do_list
Helps you track your tasks.

# Todo List

A simple project and task management app built with vanilla JavaScript.

This project was made to practice organizing a JavaScript application into separate modules, working with objects, manipulating the DOM, and storing data using `localStorage`.

## Features

* Create and manage multiple projects
* Add todos to different projects
* Set a title, description, due date and priority for each todo
* Mark todos as complete
* Edit todo details
* Delete todos
* View todos belonging to a specific project
* Persistent data using `localStorage`
* Responsive interface

## Built With

* HTML
* CSS
* JavaScript
* Webpack
* date-fns
* Web Storage API

## How It Works

Todos are represented as JavaScript objects, while projects contain their respective todos.

The application logic is kept separate from the DOM code. This makes it easier to manage the data and update the interface without putting everything into one large file.

The data is saved to `localStorage`, so todos and projects remain available after refreshing the page.

## Project Structure

```text
src/
├── index.js
├── style.css
├── todo.js
├── project.js
├── storage.js
└── dom.js
```

The exact structure may change as the project develops, but the main idea is to keep responsibilities separated between modules.

## Getting Started

Clone the repository:

```bash
git clone <repository-url>
```

Navigate into the project:

```bash
cd todo-list
```

Install the dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Then open the local development URL provided by Webpack.

## What I Learned

This project helped me get more comfortable with:

* JavaScript modules
* Factory functions/classes
* Objects and arrays
* DOM manipulation
* Event handling
* Managing application state
* `localStorage` and JSON
* Using npm packages
* Webpack
* Separating application logic from UI logic

## Future Improvements

Some things I'd like to add in the future:

* Drag and drop for todos
* Better filtering and sorting
* Recurring tasks
* Search
* Subtasks/checklists
* More detailed project organization
* Improved mobile UI

## Credits

Built as part of my JavaScript learning journey and inspired by apps such as Todoist, Things and Any.do.
