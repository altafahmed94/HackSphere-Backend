# ⚔️ HackSphere - Cybersecurity CTF & Social Platform

A full-stack platform built with **ReactJS**, **NodeJS**, **ExpressJS**, **MongoDB**, and **EJS** to foster cybersecurity learning, discussion, and competition.

**🌐 Live:** [codeproaltaf.netlify.app](https://codeproaltaf.netlify.app)  
**📁 GitHub:** [github.com/altafahmed94/HackSphere-Backend](https://github.com/altafahmed94/HackSphere-Backend)

---

## 🧩 Tech Stack

**Frontend:**
- ReactJS
- Context API for state management
- Bootstrap (UI styling)

**Backend:**
- Node.js
- Express.js
- MongoDB
- JWT Authentication

---

## ✨ Features

### 🔐 Secure Authentication
- User registration and login
- JWT-based route protection
- Profile and session management

### 👥 Community Engagement
- Create and solve CTF (Capture The Flag) challenges
- Participate in contests with leaderboard tracking
- Forums and discussion spaces

### 💬 Interactive Communication
- Real-time chat system
- Friend requests and social interactions
- Reporting system for user-generated content

---

## 📁 Folder Structure

### Backend
/controllers -> Business logic /models -> MongoDB schemas (userModel, contestModel, ctfModel, reportModel) /routes -> API routes (userRoutes, contestRoutes, ctfRoutes, reportRoutes, adminRoutes) /utils -> Utility functions and middleware app.js -> Initializes the express app server.js -> Starts the server package.json -> Backend dependencies

shell
Copy
Edit

### Frontend
/components -> UI components (DiscussionCard, ReportPopup, Leaderboard, etc.) /context -> Global state management (ChatProvider, ChatLogics, GlobalContext) /routes -> Route definitions package.json -> Frontend dependencies

yaml
Copy
Edit

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone git@github.com:altafahmed94/HackSphere-Backend.git
cd HackSphere-Backend
2. Setup Backend
bash
Copy
Edit
cd backend
npm install
node server.js
3. Setup Frontend
bash
Copy
Edit
cd frontend
npm install
npm start
📌 Highlights
Modular architecture for scalability

Chat system using global context

CTF challenge and contest management

Admin and user role-based access

Leaderboard system to track top performers

🚀 Future Enhancements
Integrate Socket.IO for real-time chat

Admin dashboard with analytics

Image/file upload support in posts

Dark mode toggle and mobile responsiveness

👨‍💻 Author
Md Altaf Ahmed
GitHub: @altafahmed94
Live Site: codeproaltaf.netlify.app
