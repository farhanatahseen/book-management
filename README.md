Book Management System
----------------------------------
This is a simple Book Management System implemented using Java and Spring Boot. It allows users to manage books by providing (Create, Update, Delete) functionalities via RESTful APIs.

Features
-
1. Create a new book with title, author, and price.
2. Update an existing book's information by ID.
3. Delete a book by its ID.

Technologies Used
-
Java
Spring Boot
Spring Data JPA
H2 Database (for in-memory testing)
Postman (for API testing)
IntelliJ IDEA (for development)

API Endpoints
-
Create a Book
-
* URL: POST /api/books/
* Description: Create a new book with title, author, and price.\\
* Request Body:
* {
  "title": "Book Title",
  "author": "Book Author",
  "price": 29.99
}
* Response: Returns the created book object.

Update a Book
-
* URL: PUT /api/books/{book\_id}/
* Description: Update an existing book's information by ID.
* Request Body:
* {
  "title": "Updated Book Title",
  "author": "Updated Book Author",
  "price": 39.99
}
* Response: Returns the updated book object.

Delete a Book
-
* URL: DELETE /api/books/{book\_id}/
* Description: Delete a book identified by {book\_id}.
* Response: Returns a success message upon successful deletion.


