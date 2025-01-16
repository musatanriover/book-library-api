# book-library-api
Book Library API

##📌 Overview

Book Library API is a simple RESTful API built with ASP.NET Core that allows users to manage a collection of books. It provides CRUD (Create, Read, Update, Delete) operations for book management.

##🚀 Features

📚 Get all books (GET /api/book)

🔍 Get a single book by ID (GET /api/book/{id})

🆕 Add a new book (POST /api/book)

✏ Update an existing book (PUT /api/book/{id})

❌ Delete a book (DELETE /api/book/{id})

🛠 Swagger UI for API testing

🏗 Technologies Used

C#

ASP.NET Core Web API

Swagger (Swashbuckle)

.NET 6/8

Entity Framework Core (Optional for Database Support)

🔧 Installation & Setup

Prerequisites

Install .NET SDK

Clone the Repository

git clone https://github.com/your-username/book-library-api.git
cd book-library-api

Run the API

dotnet run

The API will be available at: http://localhost:5000 (or another assigned port).

Test with Swagger

After running the application, open your browser and go to:

http://localhost:5000/swagger

You can test all endpoints directly in the Swagger UI.

🔗 API Endpoints

Method

Endpoint

Description

GET

/api/book

Get all books

GET

/api/book/{id}

Get a book by ID

POST

/api/book

Add a new book

PUT

/api/book/{id}

Update an existing book

DELETE

/api/book/{id}

Delete a book by ID

📄 Example API Request & Response

Adding a New Book (POST /api/book)

Request Body:

{
  "title": "The Great Gatsby",
  "author": "F. Scott Fitzgerald",
  "genre": "Classic",
  "year": 1925
}

Response:

{
  "id": 3,
  "title": "The Great Gatsby",
  "author": "F. Scott Fitzgerald",
  "genre": "Classic",
  "year": 1925
}

🛠 Future Improvements

✅ Implement Entity Framework Core for database persistence

✅ Add authentication & authorization

✅ Implement unit and integration tests using xUnit

🤝 Contributing

Feel free to fork this repository and submit pull requests!

📜 License

This project is licensed under the MIT License.

