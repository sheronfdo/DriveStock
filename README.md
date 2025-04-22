# 🚗 DriveStock – Car Parts E-Commerce Platform

**DriveStock** is a full-featured MERN stack application designed to streamline the buying and selling of car parts. It comprises three main components:

- **Backend API**: Handles data management, authentication, and business logic.
- **Admin Panel**: Provides administrative functionalities for managing products, orders, and users.
- **Client App**: Offers a user-friendly interface for customers to browse and purchase car parts.

---

## 🧩 Project Structure

| Component      | Repository Link                                          | Description                                          |
|----------------|----------------------------------------------------------|------------------------------------------------------|
| Backend API    | [Car-Parts-E-Com](https://github.com/sheronfdo/Car-Parts-E-Com)      | Express.js server managing core functionalities.     |
| Admin Panel    | [DriveStock-admin](https://github.com/rashsvr/DriveStock-admin)      | React-based dashboard for administrative tasks.      |
| Client App     | [DriveStock-client](https://github.com/rashsvr/DriveStock-client)    | React + Vite + Tailwind CSS frontend for customers.  |

---

## ⚙️ Technologies Used

- **Frontend**: React, Vite, Tailwind CSS  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Authentication**: JWT (JSON Web Token)  
- **Deployment**: Vercel (backend), Netlify or Vercel (frontend)

---

## 📸 Screenshots

> Place images in the `screenshots/` directory and reference them here.

### Client App

![Client Home](screenshots/client-home.png)  
![Product Listing](screenshots/client-products.png)

### Admin Panel

![Admin Dashboard](screenshots/admin-dashboard.png)  
![Order Management](screenshots/admin-orders.png)

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB instance (local or cloud-based)

---

### 🔧 Backend Setup

```bash
git clone https://github.com/sheronfdo/Car-Parts-E-Com.git
cd Car-Parts-E-Com
npm install
```

Create a `.env` file in the root directory:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the server:

```bash
npm start
```

---

### 🛠️ Admin Panel Setup

```bash
git clone https://github.com/rashsvr/DriveStock-admin.git
cd DriveStock-admin
npm install
```

Create a `.env` file:

```env
REACT_APP_API_URL=http://localhost:5000
```

Start the development server:

```bash
npm start
```

---

### 🌐 Client App Setup

```bash
git clone https://github.com/rashsvr/DriveStock-client.git
cd DriveStock-client
npm install
```

Create a `.env` file:

```env
VITE_API_URL=http://localhost:5000
```

Start the development server:

```bash
npm run dev
```

---

## 🧪 Features Overview

### Client App

- User registration and authentication  
- Product browsing with search and filter capabilities  
- Shopping cart and checkout process  
- Order history and tracking

### Admin Panel

- Dashboard with sales analytics  
- Product and category management  
- Order processing and status updates  
- User management

### Backend API

- RESTful API endpoints for all functionalities  
- JWT-based authentication and authorization  
- MongoDB integration for data persistence  
- Robust error handling and input validation

---

## 📂 Folder Structure

> *(You can add diagrams or structured outlines here to represent the folder layout of each component.)*

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:  
   `git checkout -b feature/your-feature-name`
3. Commit your changes:  
   `git commit -m 'Add your feature'`
4. Push to the branch:  
   `git push origin feature/your-feature-name`
5. Open a pull request detailing your changes.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
