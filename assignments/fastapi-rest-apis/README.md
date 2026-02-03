# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a simple REST API using FastAPI to practice creating endpoints, handling requests and responses, and validating data with schemas.

## 📝 Tasks

### 🛠️ Create Core API Endpoints

#### Description
Set up a FastAPI application and implement CRUD-style endpoints for a resource called `Book`.

#### Requirements
Completed program should:

- Define a `Book` model with `id`, `title`, `author`, and `year`
- Implement endpoints to create, read, update, and delete books
- Return JSON responses with appropriate status codes
- Include a simple in-memory list to store books during runtime

### 🛠️ Add Validation and Error Handling

#### Description
Improve your API by validating request data and handling common errors.

#### Requirements
Completed program should:

- Use Pydantic models to validate request bodies
- Return a clear error message when a book is not found
- Prevent invalid data (e.g., empty title or non-integer year)
- Provide example requests and responses in comments or docstrings
