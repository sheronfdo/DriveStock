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

📦 Car-Parts-E-Com/
├── 📁 controllers/            # Request handlers (route logic)
├── 📁 middleware/             # Express middleware (e.g., auth, role check)
├── 📁 models/                 # Mongoose models (MongoDB schemas)
├── 📁 routes/                 # Express route definitions
├── 📁 uploads/                # Uploaded images and files
├── 📄 index.js                # Entry point of the Express server
├── 📄 package.json            # Project metadata and scripts
├── 📄 package-lock.json       # Lock file for dependencies
├── 📄 vercel.json             # Vercel deployment config
├── 📄 README.md               # Project documentation
└── 📄 .gitignore              # Files to ignore in git

📦 DriveStock-admin/
├── 📁 node_modules/           # Installed dependencies (auto-generated)
├── 📁 public/                 # Public static files (favicon, images)
│   └── admin.svg
├── 📁 src/                    # Source code
│   ├── 📁 assets/             # Images, icons, etc.
│   ├── 📁 components/         # Reusable components (UI, form, table)
│   ├── 📁 pages/              # Admin pages (Dashboard, Users, Products)
│   ├── 📁 services/           # Axios API handlers
│   ├── 📁 hooks/              # Custom hooks (e.g., data fetching)
│   ├── 📁 utils/              # Utility functions
│   ├── 📁 layout/             # Layout wrappers like Sidebar, Navbar
│   ├── App.css               # App-wide styles
│   ├── App.jsx               # Root component
│   ├── main.jsx              # App entry point
│   └── index.css             # Global styles (Tailwind or plain CSS)
├── .gitignore                # Git ignore config
├── index.html                # HTML root template
├── package.json              # Project metadata and scripts
├── package-lock.json         # Dependency lock file
├── postcss.config.js         # PostCSS config
├── tailwind.config.js        # Tailwind config
├── vite.config.js            # Vite config
└── README.md                 # Admin panel documentation

📦 DriveStock-client/
├── 📁 node_modules/           # Installed dependencies (auto-generated)
├── 📁 public/                 # Static public assets (served as-is)
│   └── vite.svg
├── 📁 src/                    # Source code
│   ├── 📁 animations/         # Animation configs/assets (e.g., Lottie files)
│   ├── 📁 assets/             # Static media like images, fonts
│   ├── 📁 components/         # Reusable UI components
│   ├── 📁 context/            # React context providers
│   ├── 📁 data/               # Mock/static data or constants
│   ├── 📁 hooks/              # Custom React hooks
│   ├── 📁 pages/              # Route components/pages
│   ├── 📁 services/           # API service layers or SDKs
│   ├── 📁 utils/              # Utility/helper functions
│   ├── App.css               # Global styles for App
│   ├── App.jsx               # Root App component
│   ├── index.css             # Tailwind/global styles
│   └── main.jsx              # App entry point
├── .gitignore                # Files/folders to ignore in git
├── eslint.config.js          # ESLint config
├── index.html                # HTML entry (Vite root)
├── package.json              # Project metadata and scripts
├── package-lock.json         # Lock file for exact dependency versions
├── postcss.config.js         # PostCSS config for Tailwind
├── tailwind.config.js        # Tailwind CSS config
├── vite.config.js            # Vite bundler config
└── README.md                 # Project documentation

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
