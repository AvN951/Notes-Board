<h1 align="center">📝 Notes Board</h1>
<h3 align="center">A Fast, Clean & Modern Notes App Built with Vite + React + TailwindCSS</h3>

---

## 🚀 Overview  
Notes Board is a modern web application built with **Vite**, **React**, and **TailwindCSS**, focusing on speed, clean UI, and easy scalability.  
It provides a smooth and responsive notes-taking experience with a modular and intuitive component structure.

---
# 📝 Notes Board

A fast, minimal, and modern **Notes Application** built using **React**, **Vite**, **TailwindCSS**, **Express.js**, and **MongoDB**.  
Notes Board allows users to create, view, and manage notes with a clean UI and responsive design.

---

## 🚀 Features

- ⚡ **Fast UI** powered by Vite + React  
- 🎨 **Modern styling** using TailwindCSS  
- 📦 **REST API** backend using Express.js  
- 🗄️ **MongoDB** with Mongoose  
- 🚦 **Rate Limiting** implemented with Upstash Redis  
- 🔔 Toast notifications via react-hot-toast  
- 📱 Fully responsive design  
- 🧹 Clean project structure (Frontend + Backend)

---

## 🛠️ Tech Stack

### **Frontend**
- React.js  
- Vite  
- TailwindCSS  
- Axios  
- DaisyUI (if using)  
- React Hot Toast  

### **Backend**
- Node.js  
- Express.js  
- MongoDB + Mongoose  
- Upstash Redis (Rate Limiting)

---
## 📦 Installation STEPS

### Clone the Repository
```bash
git clone https://github.com/AvN951/Notes-Board
cd backend
```

### Create .env file in /backend folder with your own credentials and mention the below credentials
Add your MongoDB database url
Create a upstash account to get upstash redis url and token for rate limiter 
NODE_ENV can be switched to "DEPLOYMENT" OR "PRODUCTION".
```bash
MONGO_URI=mongodb+srv://naikaryan951_db_user:9VdDFr3yuB1pnftS@cluster0.hdyre6n.mongodb.net/notes_project?appName=Cluster0
PORT=5001
UPSTASH_REDIS_REST_URL="https://dear-filly-25489.upstash.io"
UPSTASH_REDIS_REST_TOKEN="AWORAAIncDJkMmYzZGUxODYyZWQ0ZDFhYmI0MmI5ZjY1OTgyNWI5NXAyMjU0ODk"
NODE_ENV=production
```

### Install Dependencies (Make Sure you have Nodejs installed)
```bash
npm run build
```

### Start Project
```bash
npm run start
```

