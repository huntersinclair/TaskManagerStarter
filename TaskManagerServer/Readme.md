# TaskManagerServer

This project was created as a starter app for Java Spring Boot for Interview Coding Assignment

## Development server

clone the repo locally.
make sure you have JavaSDK and Maven installed
navigate to project folder

## install

> mvn clean install

## run

> mvn spring-boot:run

## Project Overview

Project Brief: Create a simple web application for managing a list of tasks. The application should allow users to add, display list, view details, edit, and delete tasks. The tasks will be stored and retrieved from this backend service created using Java Spring Boot. The Frontend app will be Angular app.

### Project Requirements:
Frontend:
- Angular application with basic CRUD operations.
- Display tasks in a table or list format. Task should include Title, Description, and Due Date.
- Allow editing and deleting tasks inline or via a modal.
- Use Angular Services to interact with the backend.
- Implement form validation for adding & editing tasks.
- Include ability to delete a task from list.
- Include at least 2 data transformations 
    - one for truncating Description to 20 chars with elipses at end in the list
    - one for modifying date format when shown in list to Oct 30, 2024 format (but stored in ISO format in DB)
* Bonus points to use Material UI angular components for UI 

Backend:
- Java Spring Boot application with RESTful endpoints for task management.
- Task should include id, title, description, and duedate
- CRUD operations: Create, Read, Update, Delete.
- Use an in-memory database (like H2) for simplicity.
* Bonus points for including some type of Auth for API 

