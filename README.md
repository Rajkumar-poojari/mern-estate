# mern-estate
Real Estate app using MERN and tailwind css
A full-stack Real Estate application built with the MERN stack (MongoDB, Express, React, Node.js).
Users can register, log in, and manage property listings with create, edit, and delete functionality.
The frontend is styled using Tailwind CSS for a modern, responsive design.
Data is securely stored in MongoDB, with image uploads handled via Cloudinary.

# 🏡 Real Estate MERN App

A full-stack Real Estate application using the **MERN stack** (MongoDB, Express, React, Node.js) and styled with **Tailwind CSS**.

---

## 🚀 Features

- User authentication (JWT)
- Property listings (CRUD)
- Search and filter properties
- Image upload with Cloudinary
- Responsive UI with Tailwind CSS

---

## 🛠 Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, Axios
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Auth**: JWT
- **Other**: Multer, Cloudinary, dotenv

---

## ⚙️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/your-username/real-estate-app.git
cd real-estate-app

# 2. Backend setup
cd backend
npm install
cp .env.example .env
npm run dev

# 3. Frontend setup (in another terminal)
cd frontend
npm install
cp .env.example .env
npm run dev

# Environment Variables
backend/.env.example
PORT=5000
MONGO_URI=your_mongo_db_connection
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

#frontend/.env.example
VITE_API_URL=http://localhost:5000/api

---

##Folder Structure
real-estate-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── .env.example
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── .env.example
├── .gitignore
└── README.md




