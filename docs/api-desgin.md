# API Design

## Base URL

/api

## Authentication

### Register
POST /api/auth/register

### Login
POST /api/auth/login


## Projects

### List Projects
GET /api/projects

### Create Project
POST /api/projects

### Get Project
GET /api/projects/:id

### Update Project
PATCH /api/projects/:id

### Delete Project
DELETE /api/projects/:id


## Tasks

### List Project Tasks
GET /api/projects/:id/tasks

### Create Task
POST /api/projects/:id/tasks

### Update Task
PATCH /api/tasks/:id

### Delete Task
DELETE /api/tasks/:id
