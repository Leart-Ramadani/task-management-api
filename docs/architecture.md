# Architecture

## Architecture Style

The application will use a modular monolith with a layered architecture.

## Request Flow

Client
  ->
Routes
  ->
Middleware
  ->
Controllers
  ->
Services
  ->
Prisma
  ->
PostgreSQL

## Layers

### Routes

Define API endpoints and connect them to controllers.

### Middleware 

Handle authentication, authorization, error handling and other request-level concerns.

### Controllers

Handle HTTP requests and responses.
Controllers should not contain business logic.

### Services 

Contain the application's business logic.

### Prisma 

Provides database access through Prisma ORM.

### PostgreSQL

Stores application data

## Project Structure

src/
    controllers/
    routes/
    services/
    middleware/
    validators/
    db/
    app.js