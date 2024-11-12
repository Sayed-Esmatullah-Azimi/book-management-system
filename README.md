# Book Management System

## Project Overview

This is a full-stack application for managing a book inventory system. The backend is built with NestJS, and the frontend uses Next.js. Both parts are containerized with Docker, allowing easy deployment and setup.

## Features

- **Backend (NestJS)**
  - Basic API Endpoints:
    - `GET /books`: Retrieve all books.
    - `POST /books`: Add a new book (with validation for title and author).
  - Swagger API documentation available at `/api-docs`.
  - Basic error handling for invalid requests (e.g., missing fields in `POST /books`).

- **Frontend (Next.js)**
  - **Book List**: Displays a list of all books with an option to add a new book.
  - **Add Book Form**: A simple form to add a new book with field validation.
  - Responsive UI design, optimized for both desktop and mobile.

## Setup Instructions

### Prerequisites

Make sure you have Docker and Docker Compose installed.

### Installation and Running the Application

1. Clone the repository:

   ```bash
   git clone https://github.com/Sayed-Esmatullah-Azimi/book-management-system.git
   cd book-management-system
