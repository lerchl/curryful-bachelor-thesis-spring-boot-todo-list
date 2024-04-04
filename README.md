# Spring Boot Todo List
Original prompt:

    I want you to write a simple rest api for a todo list using spring boot.
    The todo list should be stored in memory and should be accessible
    through the following endpoints:

    - GET /todos
    - POST /todos
    - GET /todos/:id
    - PUT /todos/:id
    - DELETE /todos/:id
    - POST /todos/:id/toggle

    A todo is described by the following json object:
    {
      "id": 1,
      "title": "Buy milk",
      "completed": false
    }

## Run
Can be run with this command: `./mvnw spring-boot:run`

## Changes
All that needed to be changed were the package names and subsequent imports.
