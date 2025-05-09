# Authentication and Authorization System using JWT

This project demonstrates a secure **Authentication and Authorization** system using **JSON Web Tokens (JWT)**. The backend is built with **Node.js** and **Express**, while the frontend is developed with **React**. It provides an end-to-end example of secure user registration, login, and access control in a modern web application.

## 🔐 Features

- User registration with hashed passwords
- Login and JWT-based authentication
- Access to protected routes using tokens
- Refresh token mechanism to extend sessions
- Secure logout functionality
- Error handling and validation
- React frontend with Axios for API calls

## 🛠️ Tech Stack

### Frontend
- React
- Axios
- React Router (for route protection)

### Backend
- Node.js
- Express.js
- JWT (jsonwebtoken)
- bcrypt (password hashing)
- MongoDB or MySQL (choose based on your setup)
- dotenv (for managing environment variables)

## 🧑‍💻 How It Works

1. **Register**: User signs up with email and password (password is hashed).
2. **Login**: Server verifies credentials and returns a JWT + refresh token.
3. **Protected Routes**: User includes JWT in requests to access secure endpoints.
4. **Refresh Token**: When the JWT expires, the refresh token is used to get a new one.
5. **Logout**: Tokens are cleared and the session is invalidated.

## 🚀 Getting Started

### Prerequisites
- Node.js and npm
- MongoDB (local or Atlas) or MySQL
- Git

### Backend Setup

```bash
cd backend
npm install
# Create .env file and add your environment variables
npm run dev
