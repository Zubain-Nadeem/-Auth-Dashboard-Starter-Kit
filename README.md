# 🔐 Auth + Dashboard Starter Kit

A production-ready authentication starter template built with React, Firebase, and Tailwind CSS.


## ✨ Features

- Email/Password & Google authentication
- Password reset flow
- Protected routes with React Router
- User dashboard with profile info
- Firestore integration for user data
- Responsive Tailwind UI

---

## 🚀 Quick Start

### 1. Install Dependencies

npm install

### 2. Firebase Setup

Create `.env` file:
```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

Enable Authentication & Firestore in Firebase Console.

### 3. Run
```bash
npm start
```

---

## 📁 Project Structure

```
src/
├── components/
│   ├── Auth/          # Login, Signup, Reset pages
│   └── Dashboard/     # Protected dashboard
├── contexts/
│   └── AuthContext.jsx
├── config/
│   └── firebase.js
└── App.jsx
```

---

## 🚢 Deployment

```bash
npm run build
vercel deploy
```


**Built with ❤️ for developers**