# Task Manager API

A back-end REST API for task management built with FastAPI and SQLite.

## Features
- CRUD operations for tasks.
- FastAPI for high performance.
- SQLite database.

## Setup
1. Install dependencies: `pip install fastapi uvicorn sqlalchemy pydantic`
2. Run: `uvicorn main:app --reload`
3. Access at http://127.0.0.1:8000/docs

## Endpoints
- POST /tasks: Create task
- GET /tasks: List tasks
