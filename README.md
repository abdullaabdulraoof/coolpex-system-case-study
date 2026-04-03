# 🚚 Coolpex – Logistics & Operations Management System (Case Study)

![Status](https://img.shields.io/badge/Status-Production-success)
![Stack](https://img.shields.io/badge/Stack-MERN-blue)
![Realtime](https://img.shields.io/badge/Realtime-Socket.io-orange)
![Deployment](https://img.shields.io/badge/Deployment-AWS%20EC2-yellow)

---

## 📌 Overview

**Coolpex** is a **production-grade logistics and operations management system** built for a real client to handle **end-to-end delivery workflows, workforce management, and real-time tracking**.

This system improves operational efficiency by enabling seamless coordination between **Admins, Operators, and Field Agents**.

> ⚠️ **Note:** Source code is private due to client confidentiality. This repository presents a system-level case study.

---

## 🚀 Key Features

### 🧑‍💼 Admin Dashboard
- Centralized control over all operations
- Manage users, drivers, and tasks
- Monitor real-time system activity
- View analytics and operational insights

### 🚛 Operations & Workflow Management
- Task/job assignment system
- Status tracking (Pending → In Progress → Completed)
- Role-based access control (RBAC)
- Efficient job lifecycle handling

### 📡 Real-Time Updates
- Live data synchronization using **Socket.io**
- Instant updates on task status and assignments
- Event-driven architecture

### 📍 Tracking & Monitoring
- Real-time tracking of field operations
- Location-based updates
- Improved visibility of workforce activities

### 📦 Media & File Handling
- Image/document uploads using **Cloudinary**
- Optimized storage and fast delivery

---

## 🏗️ System Architecture


Frontend (Angular)
↓
Backend API (Node.js + Express)
↓
Database (MongoDB)
↓
Realtime Layer (Socket.io)
↓
Cloud Services (AWS EC2, Cloudinary)


---

## 🛠 Tech Stack

### Frontend
- Angular
- Tailwind CSS
- TypeScript

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)

### Real-Time Communication
- Socket.io

### Cloud & Deployment
- AWS EC2 (Ubuntu)
- Nginx (Reverse Proxy)
- PM2 (Process Manager)
- Certbot (SSL/HTTPS)

### Media Handling
- Cloudinary

---

## ⚙️ Deployment Architecture

### 🔹 Backend
- Hosted on AWS EC2
- Managed using **PM2**
- Auto-restart and background execution

### 🔹 Frontend
- Angular build served via **Nginx**
- Optimized static delivery

### 🔹 Reverse Proxy
- `/` → Frontend  
- `/api` → Backend  
- `/socket.io` → WebSocket server  

### 🔹 Security
- HTTPS enabled using **Certbot (Let's Encrypt)**

---

## 📸 Screenshots

> Add screenshots for better impact


/screenshots/dashboard.png
/screenshots/admin-panel.png
/screenshots/realtime-tracking.png
/screenshots/job-management.png


---

## 🧠 My Role & Contributions

- Designed full-stack system architecture
- Built backend APIs using **Node.js & Express**
- Implemented real-time communication with **Socket.io**
- Developed frontend using **Angular**
- Deployed system on **AWS EC2**
- Configured **Nginx + SSL**
- Integrated **Cloudinary**
- Optimized performance and scalability

---

## ⚡ Challenges & Solutions

### 🔴 Real-Time Data Sync
Ensuring instant updates across users  

✅ Solution: Used **Socket.io event-driven architecture**

---

### 🔴 Deployment & Uptime
Maintaining backend reliability  

✅ Solution: Used **PM2 + Nginx**

---

### 🔴 Media Storage
Handling large uploads  

✅ Solution: Integrated **Cloudinary CDN**

---

## 📈 Key Highlights

- Production-level application
- Real client project
- Full-stack + DevOps experience
- Real-time architecture
- Cloud deployment (AWS)

---

## 🔮 Future Enhancements

- Advanced analytics dashboard
- AI-based optimization
- Notification system (SMS/Push)
- Mobile app integration

---

## 📜 Disclaimer

This project was developed for a client.  
The source code is **not publicly available** due to confidentiality agreements.

---

## 👨‍💻 Author

**Abdulla Abdul Raoof**  
AI Engineer | Full Stack Developer | Edge AI Specialist  

🔗 GitHub: https://github.com/abdullaabdulraoof  
🔗 Portfolio: https://abdullaabdulraoof.github.io/portfolio/  

---

## ⭐ Final Note

If you find this case study useful, feel free to ⭐ the repository!
