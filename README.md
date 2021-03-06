The purpose of this todo app to simply showcase and explore different aspects and technologies for fullstack development in a Node.js environment. This includes,
- frontend development with React, Typescript, and ecosystem
- backend development with Node.js, Typescript, and ecosystem,
- database setup, and more.

# Description

This project is a todo application which allows users to create task items. These task items will contain a description, due date, and priority (High, Low, Medium). The API for this todo list can be found [here](https://github.com/brandiwerner/todo-api).

## Features

### All Todos

The all todo page will show the user all of their todos that they have created.

### Completed Todos

**Note: This page is still being created.**
The completed todo page will show the user all of their completed todos.

### Calendar

**Note: This page is still being created.**
The calendar page will display a calendar using react-datepicker. Underneath the calandar will be a list of todos for the current date selected.

### Create Todo

The created todo page can be accessed via the `+` button on all the pages. The create todo page is a form page where the user will create a new todo.

## Building and Running

**Note: This application will not work without running the api for it. The API for this todo list can be found [here](https://github.com/brandiwerner/todo-api).**
1. Clone this repo
2. Install packages via `npm i`
3. Run application via `npm run start`
4. Open browser to `http://localhost:3000/`

## Known Issues
* Several A11y Issues
* 2 Toast errors are being displayed instead of one

## Future Implementations/Work

* Implement Tests
* Add a legend for task coloring
* Add user sessions and authentication
* Docker and docker-compose implementation
* Add pull to refresh. 
  * This will allow the user to quickly refresh the data if an error occurs
* Add aging for completed tasks.
  * Once a complete task's age surpasses a specified threshhold perminently delete it. Potentially change the Completed page to a 'Completed within the last week' page.