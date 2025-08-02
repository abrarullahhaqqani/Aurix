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

- 🗣️ Voice Interaction: Users can talk to the assistant via the Web Speech API.
- 🧠 Gemini AI Replies: Integrated smart reply engine using Google Gemini Pro API.
- 🔐 JWT Authentication: Secure signup/login system with encrypted passwords.
- 🖼️ Custom Avatar: Upload and personalize assistant image using Cloudinary + Multer.
- 🎨 Personalization: Change assistant name, branding, and voice.
- 📱 Responsive UI: Works on desktop, tablet, and mobile.
- ☁️ Free Deployment: Easily deployed using Render and Vercel.

---

## 🧰 Tech Stack

| Layer           | Technologies Used           |
|------------------|-----------------------------|
| Frontend         | React, Tailwind CSS         |
| Backend          | Node.js, Express.js         |
| AI Integration   | Gemini AI, Web Speech API   |
| Authentication   | JWT, bcryptjs               |
| File Upload      | Multer, Cloudinary          |
| Database         | MongoDB                     |
| Deployment       | Render (Backend), Render (Frontend) |

---

## 📦 Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/abrarullahhaqqani/Aurix.git
   cd Aurix
2. **Install Dependencies**
   ```bash
   Frontend setup
   cd frontend
   npm install

   Backend setup
   cd ../backend
   npm install

3. **Setup Environment Variables**
   ```bash

   Create backend/.env and add:
   MONGODB_URI=your_mongo_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_api_key
   CLOUDINARY_API_SECRET=your_api_secret
   Create frontend/.env and add:
   VITE_API_BASE_URL=http://localhost:5000

4. **Run the Application**
   ```bash
   # Start backend server
   cd backend
   npm run dev

   # Open a new terminal
   cd frontend
   npm run dev


## 🔮 Future Scope

1. 🧑‍🤝‍🧑 Group AI Conversations

2. 🌍 Multi-language AI assistant

3. 🧠 Persistent Assistant Memory

4. 📊 User analytics and chat history

5. 📱 React Native version (mobile app)

6. 🤝 Contributing
   
## Contributions are welcome! 🚀

1. Fork the repository

2. Create your branch: git checkout -b feature/your-feature-name

3. Commit your changes: git commit -m "Add: Your feature"

4. Push to the branch: git push origin feature/your-feature-name

5. Open a Pull Request










