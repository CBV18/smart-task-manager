# README.md

````markdown
# Smart Task Manager

Smart Task Manager is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application helps users organize their daily tasks efficiently by providing secure authentication and complete task management functionality.

## Features

- User Registration and Login
- JWT-based Authentication
- Create, Read, Update, and Delete Tasks
- Mark Tasks as Completed or Pending
- Responsive User Interface
- Secure Password Hashing using bcrypt
- RESTful API Architecture

## Tech Stack

### Frontend
- React.js
- Vite
- Axios
- CSS

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- bcryptjs
- dotenv

## Project Structure

Smart-Task-Manager/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── .env
│   ├── index.js
│   └── package.json
│
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── pages/
    │   ├── context/
    │   └── App.jsx
    └── package.json

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd Smart-Task-Manager
````

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start the backend server:

```bash
npm run dev
```

### 3. Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

### 4. Open the Application

Visit:

```text
http://localhost:5173
```

## API Endpoints

### Authentication

* POST `/api/auth/register`
* POST `/api/auth/login`

### Tasks

* GET `/api/tasks`
* POST `/api/tasks`
* PUT `/api/tasks/:id`
* DELETE `/api/tasks/:id`

## Database Schema

### User

* name
* email
* password

### Task

* title
* description
* completed
* createdAt

## Learning Outcomes

This project demonstrates:

* Building modular MERN stack applications
* Implementing secure authentication with JWT
* Using MongoDB Atlas for cloud database management
* Developing REST APIs with Express.js
* Managing frontend state with React
* Using Git and GitHub for version control
* Debugging and resolving backend connectivity issues

## Future Enhancements

* Task priority levels
* Due dates
* Search and filter functionality
* Dark mode
* Deployment to cloud platforms

## Author

Chandan B V

## License

This project is developed for academic purposes as part of a Full Stack Development assignment.

```
```
