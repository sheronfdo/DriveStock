# 🚗 DriveStock – Car Parts E-Commerce Platform
DriveStock is a full-featured MERN stack application designed to streamline the buying and selling of car parts. It comprises three main components

- **Backend API**:Handles data management, authentication, and business logic
- **Admin Panel**:Provides administrative functionalities for managing products, orders, and users
- **Client App**:Offers a user-friendly interface for customers to browse and purchase car parts

---

## 🧩 Project Structure
| Component      | Repository Link                                      | Description                                   |
|----------------|------------------------------------------------------|-----------------------------------------------|
| Backend API    | [Car-Parts-E-Com](https://github.com/sheronfdo/Car-Parts-E-Com) | Express.js server managing core functionalities. |
| Admin Panel    | [DriveStock-admin](https://github.com/rashsvr/DriveStock-admin) | React-based dashboard for administrative tasks. |
| Client App     | [DriveStock-client](https://github.com/rashsvr/DriveStock-client) | React + Vite + Tailwind CSS frontend for customers.|

---

## ⚙️ Technologies Used

- **Frontend** React, Vite, Tailwind CS
- **Backend** Node.js, Express.s
- **Database** MongoB
- **Authentication** JWT (JSON Web Token)
- **Deployment** Vercel (for backend), Netlify or Vercel (for fronten)

---

## 📸 Screenshot

*Add relevant screenshots here to showcase the application's features and interfaces. Place images in a `screenshots/` directory and reference them as shown belo:*

### Client Ap

![Client Home](screenshots/client-home.pg
![Product Listing](screenshots/client-products.pg)

### Admin Pane

![Admin Dashboard](screenshots/admin-dashboard.pg
![Order Management](screenshots/admin-orders.pg)

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higer)
- npm or arn
- MongoDB instance (local or cloud-baed)

### Backend Setup
1. Clone the backend repositry:
   ```bash
   git clone https://github.com/sheronfdo/Car-Parts-E-Com.git
   cd Car-Parts-E-Com
   ```

2. Install dependences:
   ```bash
   npm install
   ```

3. Configure environment variabes:
  - Create a `.env` file in the root directry.
  - Add the following variabes:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
4. Start the serer:
   ```bash
   npm start
   ```


### Admin Panel Setup
1. Clone the admin panel repositry:
   ```bash
   git clone https://github.com/rashsvr/DriveStock-admin.git
   cd DriveStock-admin
   ```

2. Install dependences:
   ```bash
   npm install
   ```

3. Configure environment variabes:
  - Create a `.env` file in the root directry.
  - Add the following variale:
     ```env
     REACT_APP_API_URL=http://localhost:5000
     ```
4. Start the development serer:
   ```bash
   npm start
   ```


### Client App Setup
1. Clone the client app repositry:
   ```bash
   git clone https://github.com/rashsvr/DriveStock-client.git
   cd DriveStock-client
   ```

2. Install dependences:
   ```bash
   npm install
   ```

3. Configure environment variabes:
  - Create a `.env` file in the root directry.
  - Add the following variale:
     ```env
     VITE_API_URL=http://localhost:5000
     ```
4. Start the development serer:
   ```bash
   npm run dev
   ```


---

## 🧪 Features Overview

### Client Ap

- User registration and authentictio
- Product browsing with search and filter capabiltie
- Shopping cart and checkout prces
- Order history and traking

### Admin Pane

- Dashboard with sales analtic
- Product and category managmen
- Order processing and status upate
- User managment

### Backend AP

- RESTful API endpoints for all functionaltie
- JWT-based authentication and authoriztio
- MongoDB integration for data persisenc
- Error handling and input validtion

---

## 📂 Folder Strucure

*This section can include diagrams or descriptions of the folder structures for each component to aid developers in understanding the project laout.*

---

## 🤝 Contribting

Contributions are welcome! Please follow thesesteps:

1. Fork the repoitor.
2. Create a new branch: `git checkout -b feature/your-featurename.
3. Commit your changes: `git commit -m 'Add your feaure'.
4. Push to the branch: `git push origin feature/your-featurename.
5. Open a pull request detailing your canges.

---

## 📄 Lcense

This project is licensed 
