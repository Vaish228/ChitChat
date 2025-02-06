# ChitChat

## 🔍 Overview
This real-time chat application facilitates seamless communication between users through text, images, videos, and optional video calls. It includes authentication, friend management, online/offline status indicators, notifications, and customizable settings. Built with React.js, Redux Toolkit, Socket.io, Node.js, and MongoDB, the app ensures a responsive and smooth user experience.

## 🎯 Objective
The primary goal of this application is to provide a secure and efficient real-time chat platform. It enables users to connect instantly, manage friendships, exchange multimedia, and customize their chat experience with various settings.

## 🔄 Project Workflow

### **1️⃣ Authentication**
- Users can sign up and log in using JWT-based authentication.
- Secure password handling with bcrypt.js.
- Optional email verification for enhanced security.

### **2️⃣ Main Chat System**
- One-on-one real-time messaging with indicators for message status (sent, delivered, seen).
- Online/offline status tracking.
- Notifications for new messages and friend requests.
- Typing indicators and timestamps.
- Support for text, images, and video sharing.

### **3️⃣ Profile Management**
- Users can update their profile, including username, bio, and profile picture.
- Option to change email/password.
- Ability to set availability status (online/busy/offline).

### **4️⃣ Friend System**
- Send, accept, or decline friend requests.
- View friend list with online/offline indicators.
- Block/unblock users as needed.

### **5️⃣ Media & Video Call (Optional)**
- Image and video sharing with Cloudinary for storage.
- File preview before sending.
- 1-on-1 video calls using WebRTC.
- Mute audio/video options and call notifications.

### **6️⃣ Settings & Customization**
- Theme selection (dark/light mode).
- Language preferences.
- Manage notifications.

### **7️⃣ Logout & Session Management**
- Secure logout to prevent unauthorized access.
- Option to log out from all devices.

## 🗺️ Navigation

### **Authentication Pages**
✔️ Signup Page – Register new users.
✔️ Login Page – Authenticate users securely.

### **Main Chat Dashboard**
✔️ Friends List Sidebar – Displays online/offline friends.
✔️ Main Chat Window – Facilitates real-time conversations.
✔️ User Status Indicators – Shows availability status.
✔️ Notifications – Real-time alerts for messages and requests.

### **Profile Page**
✔️ Edit Profile – Update personal details.
✔️ Change Password/Email – Manage credentials securely.

### **Settings Page**
✔️ Theme & Language – Personalize UI settings.
✔️ Notifications – Control alert preferences.

### **Logout**
✔️ Secure logout to end session.
✔️ Re-login as another user when needed.

## 💡 Tech Stack & Tools

### **Frontend (User Interface)**
✅ React.js – Component-based UI.
✅ Redux Toolkit – Efficient state management.
✅ Socket.io (Client) – Enables real-time messaging.
✅ Tailwind CSS/Material-UI – Modern styling.
✅ WebRTC (Optional) – Video call implementation.

### **Backend (Server-side Logic)**
✅ Node.js with Express.js – REST API & WebSocket handling.
✅ Socket.io (Server) – Real-time communication.
✅ MongoDB (Mongoose) – NoSQL database for storing user and chat data.
✅ JWT – Secure user authentication.
✅ bcrypt.js – Password hashing.

### **Additional Services**
✅ Cloudinary/Multer – Media storage.
✅ Redis (Optional) – Real-time notification handling.
✅ WebSockets (Socket.io) – Ensures instant updates.

