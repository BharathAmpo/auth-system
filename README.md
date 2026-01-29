# Auth System

A beginner-friendly authentication system built using React, Node.js, Express, and MySQL.

## Tech Stack

- Frontend: React
- Backend: Node.js, Express
- Database: MySQL
- Authentication: Email & Password (bcrypt)

## Project Structure

```text
auth-system/
├─ backend/
│   ├── controllers/auth.controller.js
│   ├── middleware/auth.middleware.js
│   ├── routes/auth.routes.js
│   ├── .env
│   ├── db.js
│   ├── index.js
│   ├── package-lock.json
│   └── package.json
├─ frontend/
├─ .gitignore
└─ README.md
```

## Features

- User registration
- User login
- Password hashing using bcrypt

## Setup Instructions

### Backend

1. Navigate to backend folder
2. Install dependencies
3. Create `.env`
4. Start server

### Frontend

(To be added)

## Commands Used So Far

### Project Initialization

```bash
mkdir auth-system
cd auth-system
mkdir backend frontend
```

### Backend Setup

- Backend commands run **inside `backend/`**

```bash
cd backend
npm init -y
```

### Install Dependencies

```bash
npm install express mysql2 bcrypt dotenv cors
```

### Install Dev Dependency

```bash
npm install --save-dev nodemon
```

### Run Backend Server

```bash
npx nodemon index.js
```

### Git Setup

- Git commands run **from project root `auth-system/`**

```bash
git init
git add .
git commit -m " "
```

### Connect to GitHub & Push

```bash
git branch -M main
git remote add origin https://github.com/<your-username>/auth-system.git
git push -u origin main
```

## Status

🚧 In progress
