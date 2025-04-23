# Movie-MERN-Stack
<a href="https://drive.google.com/file/d/1ke5v_dJMihDtSVfw02Jd3pbaDTcmZzVW/view?usp=drive_link">Video Link</a>

# 🎬 Movie Projects

A Full Stack Web Application to manage a collection of movies with authentication and authorization.

---

## 🔥 Live Preview

(Deploy karo toh yahan link daal dena)

---

## 🛠️ Tech Stack

**Frontend:**  
- React.js  
- React Router DOM  
- Axios  
- Bootstrap or Custom CSS  

**Backend:**  
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- bcryptjs  
- jsonwebtoken (JWT)  
- dotenv  
- cors  

---

## 🚀 Features

### ✅ Authentication
- User Registration with hashed password using bcrypt
- User Login with JWT token authentication
- JWT stored in localStorage
- Protected routes based on authentication

### 🎥 Movie CRUD
- Create a new movie (Authenticated users only)
- View all movies (Public)
- Update movie details (Authenticated users only)
- Delete a movie (Authenticated users only)

### 🧠 Bonus Features (Optional)
- Role-based access (Admin/User)

---

## 🔐 API Routes

### Auth (`/auth`)
- `POST /register` - Register a new user
- `POST /login` - Login user and return JWT

### Movies (`/movies`)
- `GET /` - Get all movies
- `POST /` - Add a movie (requires token)
- `PUT /:id` - Update a movie (requires token)
- `DELETE /:id` - Delete a movie (requires token)

---

## 🧾 Movie Model

```js
{
  title: String,
  genre: String,
  director: String,
  releaseYear: Number,
  description: String
}
