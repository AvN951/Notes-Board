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
MONGO_URI= your_mongodb_url
PORT=5001
UPSTASH_REDIS_REST_URL="your_upstash_url"
UPSTASH_REDIS_REST_TOKEN="your_upstash_token"
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

## 📸 Screenshots

### 🏠 Dashboard
<img src="https://github.com/user-attachments/assets/cae92662-3dff-4c42-b929-fa482b0a29ce" width="900"/>

---

### 📋 Notes List
<img src="https://github.com/user-attachments/assets/eefa8c3a-0748-4a0d-97eb-ab6bd0a53485" width="900"/>

---

### 🔍 Navbar
<img src="https://github.com/user-attachments/assets/b9292661-8a94-47cf-9eb2-b21dd9877e96" width="900"/>

---

### ➕ Add Note
<img src="https://github.com/user-attachments/assets/6b128102-1cac-48f3-b5b8-f48752827d42" width="900"/>

---

### ⚙️ Footer / Controls
<img src="https://github.com/user-attachments/assets/e857f12b-f0eb-4d39-88a3-d12515b747ef" width="900"/>

