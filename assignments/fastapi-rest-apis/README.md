# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a modern REST API using Python and the FastAPI framework. Students will define routes, use Pydantic models for validation, and create endpoints for managing resources.

## 📝 Tasks

### 🛠️ Create a FastAPI App

#### Description
Set up a FastAPI application and create an endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Create a FastAPI app instance
- Define a `GET /` endpoint that returns a JSON welcome message
- Confirm the app starts without errors using `uvicorn`

### 🛠️ Build CRUD Endpoints for Items

#### Description
Implement endpoints to create, read, update, and delete `Item` resources using Pydantic models.

#### Requirements
Completed program should:

- Define a Pydantic model named `Item` with fields `id`, `name`, `description`, `price`, and `in_stock`
- Create endpoints for:
  - `GET /items`
  - `GET /items/{item_id}`
  - `POST /items`
  - `PUT /items/{item_id}`
  - `DELETE /items/{item_id}`
- Use an in-memory list to store items for the API session
- Return appropriate JSON responses and HTTP status codes

### 🛠️ Add Validation and Documentation

#### Description
Ensure incoming data is validated and verify the API documentation using FastAPI’s automatic docs.

#### Requirements
Completed program should:

- Use Pydantic field validation for required fields and proper types
- Return a `404` response when an item is not found
- Confirm OpenAPI docs are available at `/docs`
- Demonstrate at least one valid API request in the README or comments
