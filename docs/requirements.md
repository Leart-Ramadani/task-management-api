# Requirements

## 1. Functional Requriements

### Authentication
FR-001:
The system must allow users to create an account.

FR-002:
The systmen must allow users to login.

FR-003:
The system must reject invalid login credentials.

### Projects
FR-004:
Authenticated users must be able to create projects.

FR-005:
Users must be able to view their projects.

FR-006:
Users must be able to update their projects.

FR-007:
Users must be able to delete their projects.

### Tasks
FR-008:
Users must be able to create tasks inside a project.

FR-009:
Users must be able to assign other users to that task.

FR-010:
Users must be able to update the tasks.

FR-011:
Users must be able to delete the tasks.

FR-012:
Users must be able to filter the tasks based on the status.

FR-013:
Users must be able to change the status of the task.

## 2. Non-functional Requirements

NFR-001:
Passwords must never be stored as plain text.

NFR-002:
Protected endpoints must require authentication.

NFR-003:
Users must not be able to modify resources they are not authorized to access.

NFR-004:
The API must return appropiate status codes.

NFR-005:
The API must have automated tests for critical functionality.

## 3. Constraints
- The project must reamin small enough to be completed within 3 days.
- The API will use REST.
- PostgreSQL will be used as primary database.
- The application will initially be a modular