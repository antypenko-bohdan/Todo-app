# To-Do App

A single-page application that allows users to create and manage a list of tasks.

## Demo

[DEMO](https://antypenko-bohdan.github.io/Todo-app/)

## Technologies used

* React.js
* TypeScript
* Fetch, REST API
* classnames
* React Transition Group
* CSS

## Structure

The app is built using functional components and React Hooks. Each component is abstract and fully reusable. CSS classes are used to style the app, with conditional styling applied using the classnames library.

## Features & Functionality

### ToDos
* ToDos are stored on the server and fetched on load
* User can create a new todo
* User can delete a todo
* User can edit a todo
* User can mark a todo as completed
* User can mark all ToDos as completed
* User can delete all completed ToDos
* All changes are saved on the server
* User can filter ToDos by all, active and completed
* User can see the number of active ToDos
* In case of server error, user is notified

### Additional Features
* Animated todo list using React Transition Group
* Error handling with timed notifications
* Loader displayed during server requests

## How to run project locally

* Fork and clone this repository
* Run `npm install` to install all dependencies
* Run `npm start` to start the app
* Open http://localhost:3000 to view it in the browser.

## Dependencies

* React
* TypeScript
* classnames
* React Transition Group

## Project Structure

* `App.tsx`: Main component orchestrating the application logic
* `TodoList.tsx`: Renders the list of todos
* `TodoItem.tsx`: Represents an individual todo item
* `TodoFilter.tsx`: Provides filtering options for the todos
* `api/todos.ts`: Handles API calls for CRUD operations on todos

## Reflections

This project demonstrates proficiency in building a single-page application using React and TypeScript. It showcases the ability to work with REST APIs, handle different types of HTTP requests (GET, POST, PATCH, DELETE), and implement error handling.

The use of React Transition Group for animations adds a polished feel to the user interface, enhancing the overall user experience.

State management is handled efficiently using React's built-in hooks, demonstrating a good understanding of React's state management capabilities without the need for additional libraries.

## Future Improvements

* Implement user authentication
* Add due dates for todos
* Introduce categories or tags for better organization
* Implement a dark mode theme

Inspired by TodoMVC
