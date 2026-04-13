# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API using the FastAPI framework in Python. Learn about creating API endpoints, handling HTTP requests and responses, and using data models to manage resources.

## 📝 Tasks

### 🛠️ Set Up FastAPI Application

#### Description

Install FastAPI and create a basic application with a root endpoint that returns a welcome message.

#### Requirements

Completed program should:

- Install fastapi and uvicorn packages
- Create a FastAPI app instance
- Add a GET endpoint at "/" that returns a JSON response with a welcome message

### 🛠️ Implement CRUD Endpoints for Items

#### Description

Add endpoints to perform Create, Read, Update, and Delete operations on a collection of items (such as books or tasks).

#### Requirements

Completed program should:

- Define a Pydantic model for an Item with fields like id, name, and description
- Implement POST /items to create a new item
- Implement GET /items to retrieve all items
- Implement GET /items/{item_id} to retrieve a specific item by ID
- Implement PUT /items/{item_id} to update an existing item
- Implement DELETE /items/{item_id} to delete an item
- Use appropriate HTTP status codes and error handling