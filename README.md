# Week 4 FastAPI PostgreSQL CRUD API

## Features

- FastAPI backend
- PostgreSQL database
- Docker container setup
- CRUD operations
- SQLAlchemy ORM
- Pydantic schemas
- Swagger API testing

## Endpoints

- GET /books
- POST /books
- GET /books/{book_id}
- PUT /books/{book_id}
- DELETE /books/{book_id}

## Run Project

```bash
docker compose up -d db
uvicorn main:app --reload
```

## Swagger Docs

http://127.0.0.1:8000/docs