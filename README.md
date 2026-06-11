# 🚗 AutoHub

A modern, full-stack Car Management System built using the MERN stack (MongoDB, Express, React, Node.js) with Next.js powering the frontend.

This project demonstrates a real-world, production-style architecture for managing vehicle inventory systems, including authentication, structured data management, and scalable CRUD operations.

It is designed with a focus on clean UI, secure backend logic, and efficient data handling, making it suitable for enterprise-level vehicle or fleet management use cases.

- ✨ Key Features
- 🔐 Secure Authentication System
- User Sign Up / Sign In
- JWT-based authentication for secure session handling
- 📧 Automated Email Workflow
- Welcome email sent on registration
- Randomly generated secure password delivery
- 📊 Admin Dashboard
- Overview of total registered cars
- Quick insights into system data
- 🚘 Car Management Module
- Full CRUD operations for cars
- Fields include: make, model, color, registration number, and more
- 🗂️ Category Management
- Manage vehicle categories such as Bus, Sedan, SUV, Hatchback, etc.
- 📑 Advanced Data Tables
- Sorting and pagination for efficient data browsing
- Optimized for large datasets
- 🛡️ Data Integrity & Validation
- Strong backend validation (Express)
- Frontend validation for better UX and error handling

## Technologies Used

- Frontend: Next.js, React, TypeScript, Material-UI
- Backend: Node.js, Express, MongoDB
- Authentication: JWT (JSON Web Tokens)
- API Documentation: Swagger
- Email Service: Amazon ses (or any preferred email service)

## Prerequisites

- Node.js (>=14.x)
- MongoDB (running locally or a MongoDB Atlas account)
- Yarn or npm

## Getting Started

### Backend Setup

1. **Clone the repository**

    ```bash
    git clone https://github.com/your-username/car-management-system.git
    cd car-management-system
    ```

2. **Navigate to the backend directory**

    ```bash
    cd car-management-backend
    ```

3. **Install dependencies**

    ```bash
    npm install
    ```

4. **Create a `.env` file in the backend root directory and add the following variables:**

    ```env
    PORT=5000
    MONGO_URI=your_mongo_db_uri
    JWT_SECRET=your_jwt_secret
    EMAIL_SERVICE=your_email_service
    EMAIL_USER=your_email_user
    EMAIL_PASS=your_email_password
    ```

5. **Start the backend server**

    ```bash
    node app.js
    ```

6. **API Documentation**

   The Swagger documentation will be available at `http://localhost:5000/api-docs`.

### Frontend Setup

1. **Navigate to the frontend directory**

    ```bash
    cd ../car-management-frontend
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Create a `.env.local` file in the frontend root directory and add the following variables:**

    ```env
    NEXT_PUBLIC_API_BASE_URL=http://localhost:5000
    ```

4. **Start the frontend server**

    ```bash
    npm run dev
    ```

5. **Access the application**

   Open your browser and navigate to `http://localhost:3000`.

## Project Structure

### Backend

