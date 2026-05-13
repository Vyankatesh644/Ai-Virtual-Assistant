# 🤖 Virtual Assistant Web App

A full-stack AI-powered Virtual Assistant built using modern web technologies. This application allows users to interact with an intelligent assistant, manage authentication, and handle media seamlessly.

---

## 🚀 Features

* 🧠 AI-powered assistant (Gemini API integration)
* 🔐 User authentication (JWT-based)
* ☁️ Cloud media upload (Cloudinary)
* 📦 RESTful API with Express
* 🗂️ MongoDB database integration
* 📁 File upload support (Multer)
* ⚡ Modern frontend (Vite-based setup)

---

## 🛠️ Tech Stack

### Frontend

* HTML, CSS, JavaScript
* Vite

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* JWT Authentication

### Integrations

* Gemini AI API
* Cloudinary (media storage)

---

## 📁 Project Structure

```
virtualAssistant/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── index.js
│   └── gemini.js
│
├── frontend/
│   ├── index.html
│   └── src/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/virtualAssistant.git
cd virtualAssistant
```

### 2️⃣ Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
CLOUDINARY_API_KEY=your_key
GEMINI_API_KEY=your_api_key
```

Run backend:

```bash
npm run dev
```

---

### 3️⃣ Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

## 📸 Screenshots
### 💬 Interface
![Interface Screenshot](./interface.png)

### 🏠 Main Page
![Main Screenshot](./Main.png)

---


## 🔑 API Highlights

* `POST /api/auth/register` – Register user
* `POST /api/auth/login` – Login user
* `GET /api/user/profile` – Get user data
* `POST /api/assistant` – Interact with AI assistant

---

## 💡 Future Improvements

* Voice assistant integration 🎤
* Chat history & personalization
* Deployment (AWS / Vercel / Render)
* Mobile app version

---

## 👨‍💻 Author

**Vyankatesh Kulkarni**

---

## ⭐ Show Your Support

If you like this project, give it a ⭐ on GitHub!

---

