![Merllo](screenshots/merllo.png)

# Merllo

Merllo is a Trello clone web-based Kanban board application that helps users to manage their tasks and projects easily and efficiently. This repository contains the source code for the Merllo application, including both the backend and frontend components.

You can access the deployed application at https://merllo-0m15.onrender.com/#/.

## Navigation

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Screenshots](#screenshots)
- [Mobile](#mobile)
- [Getting Started](#getting-started)

## Features

- User registration and authentication
- Create and manage multiple boards and lists
- Add, edit, and delete tasks
- Drag and drop tasks between lists
- Assign tasks to users
- Set due dates and priority levels for tasks
- Filter tasks based on their status and priority
- Search for tasks by title or description
- Collaborate with other users on the same board

## Technology Stack

### Frontend
- Vue
- Vuex
- Vue Router
- Axios
- Scss

### Backend
- Node.js
- Express
- MongoDB
- bcrypt

## Screenshots

### Landing Page
![Landing Page](screenshots/1.png)

The Merllo landing page features a login button for a guest account or a link to the login page.

### Projects View
![Projects View](screenshots/2.png)
![Create Page](screenshots/3.png)

The projects view displays all of the projects of the user. Users can create new project with title and background.

### Board View
![Board View](screenshots/4.png)

The board view displays all of the tasks for a selected project. Users can create new tasks, move tasks between lists by dragging and dropping them, and view the details of each task by clicking on it.

### Task Details
![Task Details](screenshots/5.png)

The task details page displays all of the information for a selected task, including the title, description, due date, priority level, and assigned user. Users can edit any of the task details or delete the task entirely.

### Fast Edit
![Fast Edit](screenshots/11.png)

Allow sdut the task in a faster way.

### Sharing Page
![Sharing Page](screenshots/6.png)

Allows the user to connect new member to the project.

### Board Settings
![Board Settings](screenshots/7.png)

The board settings page allows users to edit the background of the currently selected board. It shows the last member's activities of the board.

### Project Navigation
![Project Navigation](screenshots/8.png)

Allows the user to navigate between his projects.

### Dash Board
![Dash Board](screenshots/9.png)

The Dash Board Page shows information about the current project.

### Login Page
![Login Page](screenshots/10.png)

The login page allows users to log in to their Merllo account or create a new account if they don't already have one.

## Mobile

<img src="screenshots/12.png" width=25%/><img src="screenshots/13.png" width=25%/><img src="screenshots/14.png" width=25%/><img src="screenshots/15.png" width=25%/>

## Getting Started

To run the Merllo application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `merllo-backend` directory and run `npm install` to install the backend dependencies.
3. Start the backend server by running `npm start`.
4. Navigate to the `merllo-frontend` directory and run `npm install` to install the frontend dependencies.
5. Start the frontend server by running `npm run serve`.
6. Open your web browser and navigate to `http://localhost:8080` to access the Merllo application.
