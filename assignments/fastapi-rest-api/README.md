# 📘 Assignment: FastAPI REST API

## 🎯 Objective

Learn how to build a RESTful API using the FastAPI framework in Python, including defining endpoints, handling requests, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create API Endpoints

#### Description

Build a FastAPI application with multiple endpoints for creating, reading, updating, and deleting items.

#### Requirements
Completed program should:

- Define a FastAPI app in a Python file
- Implement at least these endpoints:
  - `GET /items/` to return a list of items
  - `GET /items/{item_id}` to return a single item by ID
  - `POST /items/` to create a new item
  - `PUT /items/{item_id}` to update an existing item
  - `DELETE /items/{item_id}` to remove an item
- Use JSON for request payloads and responses

### 🛠️ Validate Data and Handle Errors

#### Description

Add request validation and error handling so the API responds correctly to invalid input and missing resources.

#### Requirements
Completed program should:

- Use Pydantic models for request and response schemas
- Validate required fields such as `name` and `price`
- Return a 404 response when an item ID is not found
- Return a 400 response for invalid request data
- Provide clear JSON error messages for failed requests
