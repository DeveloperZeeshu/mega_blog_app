# 📝 MERN Blog App

A full-stack **MERN Blog Application** that lets users **create, edit, delete, and view blog posts** — with authentication, image uploads, and Redux-powered state management. Built using modern technologies and production-style practices.

---

## 🚀 Features

- 🔐 **Hybrid Authentication** — uses both JWT and sessions for secure login & persistent auth.  
- 🧠 **Full CRUD for Posts** — users can create, read, update, and delete posts.  
- 🖼️ **Image Uploads** — supports image attachments for posts (via Multer).  
- ⚛️ **Redux State Management** — handles authentication and posts state.  
- 🧰 **Protected Routes** — frontend and backend auth guards for secure navigation.  
- 📦 **MERN Stack** — MongoDB, Express, React, Node.js.  
- 🌐 **Responsive UI** — works smoothly across devices.  

---

## 🧩 Tech Stack

### 🖥️ Frontend
- React.js (Vite)
- Redux Toolkit
- React Router DOM
- Axios

### 🧠 Backend
- Node.js + Express
- MongoDB + Mongoose
- JWT + Session
- Multer (for file uploads)

### ⚙️ Other
- dotenv for environment configs
- argon2 for password hashing
- CORS setup for API communication

---

```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/mern-blog.git
cd mern-blog
```

### 2️⃣ Install dependencies
```bash
cd server && npm install
cd ../client && npm install
```

### 3️⃣ Setup environment variables
Create `.env` in `/server` with:
```
PORT=5000
MONGO_URI=your_mongo_connection
JWT_SECRET=your_secret
SESSION_SECRET=your_session_secret
```



