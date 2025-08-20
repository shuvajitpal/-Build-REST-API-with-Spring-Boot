# Task Management REST API
## What I Built
I developed a simple REST API for task management using **Spring Boot**.  
The API supports basic **CRUD operations** (Create, Read, Update, Delete) on tasks and exchanges data in **JSON format**.  

## Why I Built It
The goal of this project was to understand and practice the fundamentals of **REST architecture**, HTTP methods, and Spring Boot annotations.  
Instead of using a database, tasks are stored in an **in-memory list**, which makes it lightweight and perfect for learning and testing with Postman.  

## How I Built It
- IDE: **Spring Tool Suite (STS) for Eclipse**  
- Build Tool: **Maven**  
- Dependency: Only **Spring Web** (no database, no JPA)  
- Controller: `TaskController` handles endpoints for creating, reading, updating, and deleting tasks.  
- Testing: Used **Postman** to send requests and verify JSON responses.

## Endpoints
- `POST /tasks` → Create a new task  
- `GET /tasks` → Get all tasks  
- `GET /tasks/{id}` → Get task by ID  
- `PUT /tasks/{id}` → Update task by ID  
- `DELETE /tasks/{id}` → Delete task by ID 
