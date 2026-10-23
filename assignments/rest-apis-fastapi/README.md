# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple REST API using FastAPI by creating endpoints, handling request data, and returning JSON responses in a clean and efficient way.

## 📝 Tasks

### 🛠️ Set Up a FastAPI App

#### Description
Create a basic FastAPI application that runs locally and exposes a simple API route for a list of items.

#### Requirements
Completed program should:

- Install and import FastAPI
- Create an app instance using `FastAPI()`
- Define at least one `GET` endpoint that returns JSON data
- Run the app locally with Uvicorn and confirm the endpoint responds successfully

### 🛠️ Create CRUD Endpoints

#### Description
Build a small API for managing a collection of books, students, or tasks using RESTful routes.

#### Requirements
Completed program should:

- Add endpoints for creating, reading, updating, and deleting records
- Use appropriate HTTP methods such as `GET`, `POST`, `PUT`, and `DELETE`
- Store data in an in-memory list or dictionary for the assignment
- Return JSON responses with clear status codes such as `200` and `201`

### 🛠️ Validate Input and Improve Responses

#### Description
Enhance the API by validating incoming JSON, returning useful error messages, and making the response structure more consistent.

#### Requirements
Completed program should:

- Use Pydantic models to validate request data
- Reject invalid input with clear error responses
- Return a structured response for successful requests
- Include at least one example request and response in the code comments or README notes
