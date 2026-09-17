# User Stories

## Authentication

### US-001 - Register

As a new user, 
I want to create an account,
so that i can use the task management system.

### Acceptance Criteria

- User provides name, email and password.
- Email must me unique.
- Password should not be stored as plain text.
- Account is created successfully.

---

### US-002 - Login

As a registered user,
I want to log in,
so i can access my projects and tasks.

### Acceptance Criteria

- Valid credentials result in successful authentication.
- Invalid credentials are rejected.
- An authentication token is returned.

--- 

## Projects

### US-003 - Create Project

As an authenticated user,
I want to create a project,
so that I can organize my tasks.

### Acceptance Criteria

- User must be authenticated.
- Project must have a name.
- Project is associated with the authenticated user.
- Created project is returned in the response.

---

## Tasks

### US-004 - Create Task

As a user,
I want to create a task inside a project,
so that i can track the work that needs to be completed.

### Acceptance Criteria

- User must be authenticated.
- Project must exist.
- User must have permission to use the project.
- Task must have a title.
- Task receives a default status.