# Driver Delivery Mobile App

A mobile application and backend system designed for delivery drivers to manage orders, track deliveries and update delivery statuses in real time.

This repository contains two main parts:
- **Nodejs_Backend** – REST APIs and business logic
- **ReactNative_Frontend** – Mobile app interface for drivers

---

## 🧠 Project Overview

The **Driver Delivery Mobile App** helps drivers:
- View and accept delivery jobs
- Track delivery status (e.g., Pending, In-Progress, Completed)
- Update order delivery details
- Navigate and view customer address information
- Efficiently manage deliveries with a user-friendly mobile UI

It’s built with a **modular architecture** separating backend APIs and frontend mobile app logic for scalability and easier development.

---

## 🔧 Technologies Used

### Backend
- Node.js
- Express.js
- REST API design
- JWT authentication (optional)
- MySQL / MongoDB (or any relational DB as configured)
- Middleware, routing, controllers

### Frontend
- React Native
- Expo (optional)
- Navigation (react-navigation)
- Axios / Fetch for REST communication
- State management

---

## 🚀 Features

#### 📲 Mobile App (React Native)
- **Driver login & authentication**
- **Dashboard** with assigned delivery tasks
- **Delivery status updates**
- **Real-time API communication**
- **Responsive UX for mobile devices**

#### ⚙️ Backend (Node.js + Express)
- REST APIs for deliveries, drivers, tasks
- CRUD operations
- Route controllers and middleware
- Async logic for performance

---

## 📁 Repo Structure

```
DriverDeliveryMobileApp
├── Nodejs_Backend
│ ├── routes
│ ├── controllers
│ ├── models
│ ├── middlewares
│ └── server.js
├── ReactNaitve_Frontend
│ ├── src
│ ├── App.js
│ └── package.json
└── README.md
```

---

## 🛠️ Installation

### Backend

```sh
cd Nodejs_Backend
npm install
# add .env configuration with DB and secret keys
npm start
```

### Frontend

```sh
cd ReactNaitve_Frontend
npm install
npx expo start
```
