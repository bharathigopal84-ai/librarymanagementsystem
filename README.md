# Library Management System

A simple Library Management System Web API developed using ASP.NET Core, Entity Framework Core, and SQL Server.

## Technologies Used

- ASP.NET Core Web API
- C#
- Entity Framework Core
- SQL Server
- Visual Studio

## Features

The application provides CRUD operations for managing books:

- Create a new book
- Get all books
- Get a book by ID
- Update an existing book
- Delete a book

## Book Details

Each book contains:

- Id
- Title
- Author
- ISBN
- PublishedYear
- IsAvailable

## API Endpoints

- GET /api/books
- GET /api/books/{id}
- POST /api/books
- PUT /api/books/{id}
- DELETE /api/books/{id}

## How to Run

1. Clone the repository.
2. Open the solution in Visual Studio.
3. Configure the SQL Server connection string in appsettings.json.
4. Apply the Entity Framework Core migrations.
5. Run the application.
6. Test the API endpoints using the included .http file or another API client.

## Project Structure

- Controllers - API controllers
- Models - Entity models
- Data - Database context
- Migrations - Entity Framework Core migrations

## Assessment

Library Management System Web API demonstrating CRUD operations using ASP.NET Core and Entity Framework Core.
