# 📓 NoteVault – Secure MERN Notes App

NoteVault is a full-stack MERN application that allows users to securely create, read, update, and delete personal notes. It uses JWT authentication for secure access and follows a clean separation between frontend, backend, and database layers.

Live demo: [https://your-frontend.onrender.com](https://notevault-frontend-b5av.onrender.com)

---

## 🚀 Features

- User authentication using JWT (Signup / Login)
- Create, edit, delete personal notes
- Protected routes (notes accessible only after login)
- RESTful APIs built with Express.js
- MongoDB Atlas for cloud database
- Fully deployed using modern DevOps practices

---

## 🛠 Tech Stack

**Frontend**
- React.js
- Context API
- Bootstrap

**Backend**
- Node.js
- Express.js
- JWT Authentication
- bcryptjs for password hashing

**Database**
- MongoDB Atlas

**Deployment**
- Backend: Render (Web Service)
- Frontend: Render (Static Site)

---

## 📂 Project Structure

NoteVault/
├── backend/
│ ├── models/
│ ├── routes/
│ ├── middleware/
│ ├── db.js
│ └── index.js
│
├── frontend/
│ ├── src/
│ ├── context/
│ └── components/

yaml
Copy code

---

## 🔐 Environment Variables

Backend environment variables (configured on Render):

MONGO_URI=your_mongodb_atlas_uri
JWT_SECRET=your_secret_key
PORT=5000

Frontend environment variable:

REACT_APP_HOST=https://your-backend-url.onrender.com/


---

## ⚙️ Installation (Local Setup)

### Backend
```bash
cd backend
npm install
npm start
Frontend
bash
Copy code
cd frontend
npm install
npm start

```

---
## 🌍 Live Deployment

Frontend: [https://your-frontend.onrender.com](https://notevault-frontend-b5av.onrender.com)
Backend API: [https://your-backend.onrender.com](https://notevault-backend-i4bi.onrender.com)

---
## 🧠 Learning Outcomes

Built secure authentication using JWT
Designed REST APIs with Express
Used Context API for global state management
Worked with MongoDB Atlas in production
Deployed a full MERN app using Render
---
## 📌 Future Improvements

Note search & filtering
Pagination
Token expiry & refresh tokens
UI enhancements with animations

---
## 👤 Author

Prashant Narwade
Aspiring Software Engineer | MERN Stack Developer
