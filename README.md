# 📚 BookStore - E-Commerce Web Application

A full-stack e-commerce web application for selling books, built with React and Spring Boot.

## 🛠️ Technologies

- **Frontend:** React 18.2.0, Material UI 5.14.20, React Router, Axios
- **Backend:** Spring Boot 3.2.0, Spring Data JPA, PostgreSQL
- **Database:** PostgreSQL

## ✨ Features

- Home page with featured books
- Book details page
- Shopping cart functionality
- Search books by title, author, or description
- Responsive design with Material UI

## 🚀 Getting Started

### Prerequisites

- Node.js 16+ and npm
- Java 17+
- Maven 3.6+
- PostgreSQL 12+

### Installation

1. **Database Setup:**
   ```sql
   CREATE DATABASE bookstoredb;
   ```
   ```bash
   psql -U postgres -d bookstoredb -f SourceCode/database/products_postgres.sql
   ```

2. **Backend:**
   ```bash
   cd SourceCode/backend
   mvn spring-boot:run
   ```
   Backend runs on `http://localhost:8080`

3. **Frontend:**
   ```bash
   cd SourceCode/frontend
   npm install
   npm start
   ```
   Frontend runs on `http://localhost:3000`

## 📡 API Endpoints

- `GET /api/books` - Get all books
- `GET /api/books/featured` - Get featured books
- `GET /api/books/{id}` - Get book by ID
- `GET /api/books/search?q={query}` - Search books
- `POST /api/books` - Create new book
- `PUT /api/books/{id}` - Update book
- `DELETE /api/books/{id}` - Delete book

## 📝 License

This project is created for educational purposes.
