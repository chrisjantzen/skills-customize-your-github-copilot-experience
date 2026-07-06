# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a simple REST API with FastAPI by defining routes, handling request data, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create Your First API Endpoint

#### Description
Build a small FastAPI application that responds to a basic request and returns a JSON message.

#### Requirements
Completed program should:

- Import `FastAPI` and create an app instance
- Define a route such as `/` that returns a welcome message
- Return a JSON response using a Python dictionary
- Run the app locally and confirm the endpoint works

### 🛠️ Add a Resource Endpoint

#### Description
Extend the API so it serves a simple collection of items through a dedicated endpoint.

#### Requirements
Completed program should:

- Define a route such as `/items` that returns a list of sample items
- Use query parameters or path parameters in at least one route
- Return structured JSON data for each item
- Include a basic error or validation example, such as a missing item ID

### 🛠️ Build a Small CRUD Example

#### Description
Create endpoints to create, read, and list a simple data resource.

#### Requirements
Completed program should:

- Define endpoints for creating and retrieving items
- Store items in memory for the duration of the program
- Use `POST` and `GET` requests to interact with the API
- Demonstrate the API with example request data
