# 📘 MERN E-learning Platform

A full-stack web application for digital learning built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This platform supports user authentication, course management, lecture viewing, admin dashboard, Razorpay payment integration, email verification, and more.

---

## 🚀 Features

### 👨‍🎓 User Features
- User registration with email verification
- Login with JWT-based authentication
- Browse and view courses
- Lecture study interface
- Razorpay payment integration
- Account and dashboard pages

### 🧑‍💼 Admin Features
- View all users
- Manage courses and lectures
- Admin dashboard with analytics

---

## 🛠️ Tech Stack

### Frontend:
- React.js + Vite
- React Router DOM
- Axios
- React Hot Toast
- React Icons

### Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- Razorpay
- Multer (for file uploads)
- Nodemailer (for emails)
- JWT + Bcrypt (for authentication)

---

## 📁 Project Structure

### 🗄️ Server Folder

```
server/
├── controllers/
│   ├── admin.js
│   ├── course.js
│   └── user.js
├── database/
│   └── db.js
├── middlewares/
│   ├── isAuth.js
│   ├── multer.js
│   ├── sendMail.js
│   └── TryCatch.js
├── models/
│   ├── Courses.js
│   ├── Lecture.js
│   ├── Payment.js
│   └── User.js
├── routes/
│   ├── admin.js
│   ├── course.js
│   └── user.js
├── uploads/
├── .env
├── index.js
├── package.json
└── package-lock.json
```

### 🧑‍🎨 Frontend Folder

```
frontend/
├── public/
│   └── vite.svg
├── src/
│   ├── admin/
│   ├── assets/
│   ├── components/
│   ├── context/
│   ├── pages/
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── index.html
├── .gitignore
├── vite.config.js
├── package.json
└── package-lock.json
```

---

## 📦 Backend Dependencies

```bash
npm install bcrypt cors dotenv express jsonwebtoken mongoose multer nodemailer razorpay uuid
npm install --save-dev nodemon
```

---

## 🔧 .env Configuration (Backend)

```env
PORT=5000
DB=your_mongodb_uri
Activation_Secret=any_random_string
Password=your_gmail_app_password
Gmail=your_gmail_address
Jwt_Sec=your_jwt_secret
Razorpay_Key=your_razorpay_key_id
Razorpay_Secret=your_razorpay_key_secret
```

---

## 📦 Frontend Dependencies

```bash
npm install axios react-hot-toast react-icons react-router-dom
```

---

## 🔐 .gitignore

```
.env
/node_modules
```

---

## ▶️ How to Run Locally

### Backend
```bash
cd server
npm install
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

Make sure the frontend is configured to call APIs on `http://localhost:5000`.

---

## 📬 Contact

Feel free to open issues or contribute via pull requests.

---

## 📄 License

This project is licensed under the MIT License.
