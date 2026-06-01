# 🏙️ CivicEye

**CivicEye** is a full-stack web application that empowers communities to report, track, and manage civic complaints efficiently. It provides an intuitive interface for users to submit issues with real-time status tracking, while administrators can view and resolve them through a streamlined dashboard.

---

## 🌐 Live Preview

**Render** : https://civiceyefrontend.onrender.com

---

## 🧩 Features

- 📝 Complaint submission with descriptions, categories, and location
- 📸 Upload proof (e.g., images) for transparency
- 📊 Admin dashboard to manage all user complaints
- 🔍 Filter, sort, and paginate complaints
- 🔒 Role-based access control (users vs admins)
- 📬 Real-time feedback using toast notifications
- 🎯 Responsive and mobile-friendly UI

---

## ⚙️ Tech Stack

**Frontend:**  
- React.js  
- Tailwind CSS  
- React Router  
- Axios  
- Vite

**Backend:**  
- Node.js  
- Express.js  
- MongoDB  
- Multer (file upload)  
- dotenv

---

<!--
## 🔮 Upcoming Features

We're actively working on making CivicEye more robust and secure. Here's what's planned next:

🔐 **JWT-based Authentication**
Secure and stateless login system using JSON Web Tokens. (In Progress)

📱 **Two-Factor Authentication (2FA)**
Add an extra layer of security with OTP/email-based verification during login.

🗺️ **Map Integration**
Display complaints visually on a map using location data (e.g., Google Maps or Leaflet.js).

📊 **Analytics Dashboard**
Graphical insights for administrators showing complaint trends, resolution rates, and more.

📥 **Admin Reports Export**
Export complaint data as CSV or PDF for official documentation or review.

📨 **Email Notifications**
Notify users when complaint status updates or responses are posted.

🌐 **Multilingual Support**
Localize the app to support regional languages for broader accessibility.

---

-->

## 📁 Folder Structure

```plaintext
CivicEye/
├── Backend/
│   ├── Controllers/          # Route logic (users, complaints)
│   ├── Models/               # Mongoose schemas
│   ├── Routes/               # Express routes
│   ├── utils/                # Utility functions
│   ├── proofs/               # Uploaded images/files
│   ├── .env                  # Environment variables
│   ├── multer.js             # File upload config
│   └── server.js             # Entry point
│
├── Frontend/civiceye
│   ├── node_modules/          # Project dependencies
│   ├── public/                # Static assets
│   ├── src/                   # Source code (components, pages, etc.)
│   ├── eslint.config.js       # ESLint configuration
│   ├── index.html             # Base HTML file
│   ├── package.json           # Project metadata and scripts
│   ├── package-lock.json      # Exact dependency versions
│   ├── tailwind.config.js     # Tailwind CSS configuration
│   └── vite.config.js         # Vite bundler configuration
│
├── README.md                  # You're reading it 🙂
└── .gitignore                 # Git ignore rules
```
