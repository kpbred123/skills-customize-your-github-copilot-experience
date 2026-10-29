# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API with FastAPI to manage a collection of books. Practice defining request models, implementing CRUD endpoints, and returning appropriate HTTP status codes.

## 📝 Tasks

### 🛠️ Set Up the API and Book Model

#### Description
Use the provided `main.py` starter file to create a FastAPI application and define the data models for books.

#### Requirements
Completed program should:

- Create a FastAPI application named `app`.
- Define a `BookCreate` model with `title` and `author` fields.
- Define a `Book` model that includes an integer `id` as well as the book's title and author.
- Store books in memory; a database is not required.


### 🛠️ Add Endpoints to Read Books

#### Description
Implement endpoints that let a client retrieve all books or look up one book by its ID.

#### Requirements
Completed program should:

- Return all books from `GET /books`.
- Return one book from `GET /books/{book_id}` when that ID exists.
- Return HTTP 404 when a requested book ID does not exist.


### 🛠️ Implement Book Creation and Updates

#### Description
Add endpoints to create, update, and delete books. Use the request model to validate incoming book data, then try the endpoints using FastAPI's interactive documentation.

#### Requirements
Completed program should:

- Create a book with `POST /books` and return HTTP 201 with the new book, including its assigned ID.
- Update a book with `PUT /books/{book_id}` and return HTTP 404 if the ID does not exist.
- Delete a book with `DELETE /books/{book_id}` and return HTTP 404 if the ID does not exist.
- Return HTTP 204 after successfully deleting a book.
- From the assignment directory, run the API with `uvicorn main:app --reload` and verify the endpoints at `/docs`.
