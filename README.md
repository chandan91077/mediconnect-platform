# 🏥 MediConnect – Healthcare Booking Platform

🚀 **Live Demo Available:**
📱 Android App: https://play.google.com/store/apps/details?id=com.mediconnect.chandan
💻 Web App: https://www.prabhatanvik.shop/

---

## 📌 Overview

MediConnect is a full-stack healthcare booking platform that enables users to connect with doctors, book appointments, and manage healthcare services seamlessly through mobile and web applications.

The platform integrates secure authentication, real-time interactions, and online payment systems to provide a smooth user experience.

---

## 🌟 Features

### 👤 User Features

* 🔐 Google Authentication (Firebase)
* 📅 Book doctor appointments
* 👨‍⚕️ View doctor profiles
* 🔔 Real-time notifications
* 💳 Secure online payments (Cashfree)

### 🧑‍⚕️ Doctor Features

* Manage availability
* View and accept appointments
* Interact with patients

### 🌐 Web Application

* Firebase Google Sign-In
* Admin/Doctor dashboard
* Appointment management system

---

## 🛠️ Tech Stack

### 📱 Mobile App

* Flutter
* Dart
* Firebase Authentication

### 🌐 Web Application

* React.js / TypeScript
* Firebase Web SDK

### 🔧 Backend

* Django / Node.js
* REST APIs

### 🗄️ Database

* PostgreSQL / MongoDB

### 🔐 Authentication

* Firebase Auth (Google Sign-In)

### 💳 Payments

* Cashfree Payment Gateway

---

## 📂 Project Structure

```
healthlink-connect/
│── mobile_app/        # Flutter mobile app
│── web_app/           # Web application (React)
│── server/            # Backend APIs
│── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/chandan91077/healthcare-booking-platform.git
cd healthlink-connect
```

---

### 2️⃣ Mobile App Setup (Flutter)

```
cd mobile_app
flutter pub get
flutter run
```

---

### 3️⃣ Web App Setup

```
cd web_app
npm install
npm run dev
```

---

### 4️⃣ Backend Setup

#### For Node.js:

```
cd server
npm install
npm start
```

#### OR for Python (Django):

```
cd server
pip install -r requirements.txt
python manage.py runserver
```

---

## 🔑 Environment Variables

Create a `.env` file in the server folder:

```
FIREBASE_PROJECT_ID=your_project_id
CASHFREE_APP_ID=your_cashfree_app_id
CASHFREE_SECRET_KEY=your_secret_key
```

---

## 🔐 Security Best Practices

* Sensitive files (API keys, serviceAccountKey.json) are not committed to Git
* Use environment variables for secrets
* Firebase Admin SDK used securely in backend

---

## 🚀 Deployment

* 📱 Mobile App: Google Play Store
* 💻 Web App: Hosted on custom domain
* 🔧 Backend: Docker / Cloud (AWS / Render)

---

## 📸 Screenshots

> Add screenshots here for better presentation (App UI, Dashboard, Booking Flow)

---

## 👨‍💻 Author

**Chandan Yadav**
📧 [chandany67071@gmail.com](mailto:chandany67071@gmail.com)
📱 +91-9682000334

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit pull requests.

---

## ⭐ Show Your Support

If you like this project, please ⭐ the repository!

---

## 📜 License

This project is licensed under the MIT License.
