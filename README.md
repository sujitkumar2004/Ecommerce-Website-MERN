# 🛒 Ecommerce Website - MERN Stack

This is a full-featured ecommerce website built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It includes essential features like user authentication, product listing, cart functionality, order management, and admin controls.

## 🚀 Features

### 👤 User
- Signup/Login with JWT authentication
- Browse all products
- Search and filter products
- Add/remove items from cart
- Checkout and place orders
- View order history

### 🛠️ Admin
- Add/edit/delete products
- View all orders
- Manage users
- Admin-only protected routes

## 🧰 Tech Stack

- **Frontend:** React.js, React Router, Axios, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MongoDB with Mongoose
- **Authentication:** JWT (JSON Web Tokens)
- **File Uploads:** Multer
- **Environment Config:** dotenv


## 📦 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sujitkumar2004/Ecommerce-Website-MERN.git
cd Ecommerce-Website-MERN
PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
# Start backend
cd backend
npm run dev

# Start frontend
cd ../frontend
npm start


