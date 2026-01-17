# 🎓 CampusSetu – Alumni Management System

CampusSetu is a full-stack web application designed to efficiently manage and strengthen the relationship between educational institutions and their alumni. It provides a centralized platform for alumni data management, communication, events, and networking.

---

## 📌 Project Description

Alumni are a vital part of any institution’s ecosystem. CampusSetu aims to bridge the gap between alumni and their alma mater by offering a digital platform where alumni can stay connected, update their profiles, participate in events, and contribute to the growth of the institution.

This system reduces manual record-keeping and improves engagement through a structured and user-friendly approach.

---

## ✨ Key Features

### 🔐 Authentication & Roles
- Secure user authentication
- Role-based access (Admin & Alumni)

### 🧑‍💼 Admin Module
- Manage alumni records
- Create and manage events
- Post announcements and updates
- View alumni activity and engagement

### 🎓 Alumni Module
- Profile creation and updates
- View events and announcements
- Connect with fellow alumni
- Participate in institutional activities

---

## 🛠️ Technology Stack

| Layer | Technology |
|------|-----------|
| Frontend | React.js (Vite) |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| API | RESTful APIs |
| Version Control | Git & GitHub |

---

## 📁 Project Structure

```
CampusSetu-Alumni-Management-System/
├── backend/        # Server-side logic and APIs
├── frontend/       # Client-side UI
├── .gitignore
├── package.json
```
---

## ⚙️ Installation & Setup

Follow the steps below to run the project locally:

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Nishita-Jha/CampusSetu-Alumni-Management-System.git
cd CampusSetu-Alumni-Management-System
```

### 2️⃣ Install Dependencies
Backend
```bash
cd backend
npm install
```
Frontend
```bash
cd ../frontend
npm install
```

### 3️⃣ Environment Configuration
Create a .env file in the backend directory and configure:
```env
PORT=5000
MONGO_URI=your_database_url
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the Application
```bash
# Start backend
cd backend
npm start

# Start frontend
cd ../frontend
npm run dev
```
---

### 🧪 Usage
- Admin can manage alumni data, events, and announcements.
- Alumni can register, update profiles, and stay connected with the institution.
- The platform enables structured communication and long-term alumni engagement.

---

**⭐ If you found this project helpful, feel free to star the repository !!**
