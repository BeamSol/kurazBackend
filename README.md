# Simple Task Manager API

A basic REST API for managing tasks built with Express.js.

## Features

- `GET /api/tasks` — Get all tasks
- `POST /api/tasks` — Add a new task (JSON body: `{ "title": "Task title" }`)
- `PUT /api/tasks/:id` — Mark a task as completed
- `DELETE /api/tasks/:id` — Delete a task

## Setup

1. Clone the repo or copy the files.
2. Run `npm install` to install dependencies.
3. Create an empty `tasks.json` file in the project root with content: `[]`.
4. Start the server:
   ```bash
   node index.js
