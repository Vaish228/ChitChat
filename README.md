# ChitChat

## 📌 Overview
A real-time chat application that allows users to communicate via text, images, videos, and video calls (optional). It includes authentication, friend management, online/offline status indicators, notifications, and customization options. Built with React.js, Redux Toolkit, Socket.io, Node.js, and MongoDB for a seamless experience.

## 🎯 Objective
To provide a secure and efficient real-time chat platform with instant messaging, media sharing, and user customization features.

## 🔄 Workflow

### **📝 Pages**
- **Authentication** – Signup & login with JWT authentication.  
- **Main Chat** – Chat interface with friends list, status indicators, and real-time messaging.  
- **Profile** – Update username, bio, and profile picture.  
- **Settings** – Customize theme, language, and notifications.  
- **Logout** – Securely end the session and re-login as another user.  

### **🗺️ Navigation**
- **Friends List** – Displays online/offline friends.  
- **Chat Window** – Real-time conversations with multimedia support.  
- **Notifications** – Alerts for messages & friend requests.  
- **Profile & Settings** – Manage user details, credentials, and preferences.  

### **👥 Users & Roles**
- **Registered Users** – Can chat, manage friends, and customize settings.  
- **Admin (Optional)** – Can manage users and monitor reports (if implemented).  

## 💡 Tech Stack

### **Frontend**
✅ React.js, Redux Toolkit, Socket.io (Client)  
✅ Tailwind CSS / Material-UI  
✅ WebRTC (Optional – Video Calls)  

### **Backend**
✅ Node.js, Express.js, Socket.io (Server)  
✅ MongoDB (Mongoose), JWT Authentication  
✅ bcrypt.js – Secure password handling  

### **Additional Services**
✅ Cloudinary/Multer – Media storage  
✅ Redis (Optional) – Real-time notifications  
✅ WebSockets (Socket.io) – Instant updates  

