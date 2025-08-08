# 💬 Real-Time Chat Application

A sleek and responsive **real-time chat application** built with **React.js** and **Firebase**, allowing users to send and receive messages instantly. Deployed with ❤️ using **Vercel**.

---

## 🚀 Live Demo

👉 [Click here to chat live](https://chat-app-sable-psi.vercel.app/)  

---

## 🛠️ Tech Stack

- ⚛️ **React.js** – Frontend library
- 🔥 **Firebase** – Authentication + Firestore (for real-time database)
- ☁️ **Vercel** – For deployment - 🖼️ **HTML5** – Markup language
- 🎨 **CSS3** – Styling and layout
- 💻 **JavaScript (ES6+)** – Core scripting
- 🖼️ **HTML5** – Markup language
- 🌳 **Git & GitHub** – Version control and repository hosting

---

## ✨ Features

- 🔐 Google Sign-In Authentication
- 💬 Real-time messaging via Firebase Firestore
- 👥 Multi-user chat
- 🧼 Auto-scroll to latest messages
- 🌓 Responsive UI
- 🧾 Profile update & image upload
- 🔒 Secure data storage and access rules

---

## 📁 Project Structure

chat-app/
├── public/
├── src/
│ ├── components/
│ │ ├── ChatBox.jsx
│ │ ├── LeftSidebar.jsx
│ │ ├── RightSidebar.jsx
│ │ ├── Message.jsx
│ │ 
│ ├── pages/
│ │ ├── Chat.jsx
│ │ ├── Login.jsx
│ │ └── ProfileUpdate.jsx
│ │
│ ├── lib/
│ │ └── upload.js
│ │
│ ├── App.jsx
│ ├── index.js
│ └── firebase-config.js
│
├── .env
├── package.json
├── README.md

🌍 Deployment with Vercel
Push your code to a GitHub repo

Go to https://vercel.com

Import your GitHub repository

Set up required environment variables (if using .env)

Deploy — your chat app will go live!

| Feature             | Tech Used          |
| ------------------- | ------------------ |
| Google Auth         | Firebase Auth      |
| Real-Time Messaging | Firebase Firestore |
| Image Upload        | Firebase Storage   |
| User Profile Update | Custom Page        |
| File Handling       | `upload.js` module |


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
