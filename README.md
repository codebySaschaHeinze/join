# Join

Join is a task management web application with a Kanban-style board for organizing work across different task stages. It includes task, contact, and authentication flows in a responsive Angular frontend.

## Live Demo

[https://join.saschaheinze.de](https://join.saschaheinze.de)

## Tech Stack

- Angular 20
- TypeScript
- SCSS
- Angular CDK
- Firebase
- AngularFire
- RxJS
- Jasmine and Karma

## Features

- User registration and login with Firebase Authentication
- Guest login flow
- Protected application routes for authenticated users
- Summary dashboard with task counts, urgent tasks, and upcoming deadlines
- Kanban board with columns for To Do, In Progress, Await Feedback, and Done
- Drag-and-drop task status updates using Angular CDK
- Task search by title, description, category, and subtasks
- Task creation with title, description, due date, category, priority, assigned contacts, and subtasks
- Task detail dialog with editing, deletion, and subtask completion
- Contact management with add, edit, delete, detail view, and alphabetical grouping
- Responsive layouts for desktop and mobile views

## Project Context

Join was developed as part of my Developer Akademie training. The project is based on a course task and was implemented to practice building a structured Angular application with authentication, task management, contact management, and responsive UI behavior.

## Local Setup

Install the project dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

Open the app in your browser at:

```text
http://localhost:4200/
```

Build the project for production:

```bash
npm run build
```

Run the test suite:

```bash
npm test
```

## Project Status

Join is a completed portfolio project and remains available for demonstration and code review purposes.
