# 🎟️ Ticket System - Frontend

Frontend application for the Event Ticketing System, built with
**ReactJS** to provide a modern and responsive user interface for
booking tickets and managing events.

------------------------------------------------------------------------

## 🚀 Overview

This frontend app allows users to: - Browse and search events - Select
seats and book tickets - Manage orders and view ticket history -
Interact with admin features (if authorized)

It communicates with the backend via RESTful APIs.

------------------------------------------------------------------------

## 🏗️ Tech Stack

-   ReactJS
-   TypeScript (if applicable)
-   Vite
-   Axios
-   React Router
-   CSS / TailwindCSS

------------------------------------------------------------------------

## 📁 Project Structure

    frontend/
    ├── src/
    │   ├── assets/
    │   ├── components/
    │   ├── pages/
    │   ├── services/
    │   ├── hooks/
    │   ├── utils/
    │   ├── types/
    │   ├── App.jsx / App.tsx
    │   └── main.jsx / main.tsx
    ├── public/
    ├── package.json
    └── vite.config.js

------------------------------------------------------------------------

## ⚙️ Prerequisites

-   Node.js 18+
-   npm or yarn

------------------------------------------------------------------------

## 🔧 Setup & Run

``` bash
cd frontend
npm install
npm run dev
```

App runs at: http://localhost:5173

------------------------------------------------------------------------

## 🔗 Backend Integration

Make sure backend is running at: http://localhost:8080

Update API base URL in: src/services/api.js

------------------------------------------------------------------------

## 🔑 Features

### 👤 User

-   Register / Login (JWT Authentication)
-   Browse and search events
-   View event details
-   Select seats
-   Book tickets
-   View order history
-   Download tickets

### 🛠️ Admin

-   Manage events & venues
-   Manage users
-   Ticket check-in (QR code)
-   Dashboard management

------------------------------------------------------------------------

## 🔌 API Communication

-   Axios for HTTP requests
-   JWT Authentication
-   Centralized API service layer

------------------------------------------------------------------------

## 📌 Notes

-   Scalable folder structure
-   Component-based architecture
-   Integrated with Spring Boot backend

