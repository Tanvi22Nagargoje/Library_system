# Library_system
Backend: Node.js with Express.js

# Library Management System

A full-stack Library Management System built using Node.js, Express.js, Sequelize, PostgreSQL, and React.js. This system allows users to manage books, borrow books, and view borrowing history. Admins can also manage users and their borrowing records.

## Features

- **User Registration and Authentication**: Users can register, log in, and manage their profiles.
- **Book Management**: Admins can add, update, delete, and view books in the library.
- **Borrowing Books**: Users can borrow books, and admins can track borrowed books and due dates.
- **User Borrowing History**: Users can see the books they have borrowed along with due dates.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL with Sequelize ORM
- **Frontend**: React.js (for frontend, if applicable)
- **Authentication**: JSON Web Tokens (JWT) for authentication

## API Endpoints

### **Books API**
- **GET** `/api/books`: Get a list of all books.
- **GET** `/api/books/:id`: Get a specific book by its ID.
- **POST** `/api/books`: Add a new book.
- **PUT** `/api/books/:id`: Update a book by ID.
- **DELETE** `/api/books/:id`: Delete a book by ID.

### **Users API**
- **GET** `/api/users`: Get a list of all users.
- **GET** `/api/users/:id`: Get a specific user by ID.
- **POST** `/api/users`: Register a new user.
- **PUT** `/api/users/:id`: Update a user's information.
- **DELETE** `/api/users/:id`: Delete a user.

### **Borrowing API**
- **GET** `/api/borrowings`: Get a list of all borrowing records.
- **POST** `/api/borrowings`: Borrow a book.
- **PUT** `/api/borrowings/:id`: Update the return date of a borrowed book.
- **DELETE** `/api/borrowings/:id`: Delete a borrowing record.

## Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v12.x or higher)
- [PostgreSQL](https://www.postgresql.org/)

### 1. Clone the repository
```bash
git clone https://github.com/your-username/library-management-system.git
cd library-management-system
