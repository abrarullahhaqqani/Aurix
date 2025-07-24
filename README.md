# 💬 Aurix – AI-Powered Virtual Assistant

Aurix is a full-stack AI-powered virtual assistant that interacts with users using **voice and text**, just like JARVIS! Built using the **MERN stack** and enhanced with **Gemini AI**, this assistant can understand, respond, and be completely customized to suit your needs.

> 🧠 Voice + AI | Authentication | Custom Assistant Avatar | Real-Time Responses | Fully Deployed

---

## 🌐 Live Demo

🔗 [Aurix Live App](https://aurix-fronted.onrender.com)  
📦 [GitHub Repository](https://github.com/abrarullahhaqqani/Aurix)

**Demo Credentials:**
Email: PAV@gmail.com
Password: 123456


---

## 🚀 Features

- 🗣️ **Voice Interaction**: Users can talk to the assistant via the Web Speech API.
- 🧠 **Gemini AI Replies**: Integrated smart reply engine using Google Gemini Pro API.
- 🔐 **JWT Authentication**: Secure signup/login system with encrypted passwords.
- 🖼️ **Custom Avatar**: Users can upload and customize the assistant image using Cloudinary + Multer.
- 🎨 **Personalization**: Change assistant name, branding, and voice.
- 📱 **Responsive UI**: Works on desktop, tablet, and mobile.
- ☁️ **Free Deployment**: Easily deployed using Render for backend and Vercel/Render for frontend.

---

## 🧰 Tech Stack

| Layer           | Technologies Used |
|------------------|-------------------|
| Frontend         | React, Tailwind CSS |
| Backend          | Node.js, Express.js |
| AI Integration   | Gemini AI (Google), Web Speech API |
| Authentication   | JWT, bcryptjs |
| File Upload      | Multer, Cloudinary |
| Database         | MongoDB |
| Deployment       | Render (Backend), Vercel/Render (Frontend) |

---

## 📦 Installation

### 1. Clone the Repository
```bash
git clone https://github.com/abrarullahhaqqani/Aurix.git
cd Aurix

### 2. Install Dependencies
# Frontend setup
cd frontend
npm install

# Backend setup
cd ../backend
npm install

### 3.  Setup Environment Variables
backend/.env

MONGODB_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

frontend/.env

VITE_API_BASE_URL=http://localhost:5000

##4. Run the Application
# Backend
cd backend
npm run dev

# Frontend (in another terminal)
cd frontend
npm run dev

## 


