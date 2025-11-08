
# E-Commerce Full Stack Web Application

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Tech Stack](https://img.shields.io/badge/Stack-React%20%2B%20Spring%20Boot-green)]()

## Overview

This is a full-stack e-commerce web application developed using **React** (frontend) and **Spring Boot** (backend).
The application provides users with a complete online shopping experience, including product catalog browsing, cart management, secure payment integration, and an administrative dashboard for managing products and orders.

The project demonstrates skills in **full-stack web development**, **RESTful API design**, and **database management** using industry-standard technologies.

---

## Tech Stack

### Frontend

* React.js – component-based UI library
* Redux – state management
* Axios – API communication
* Tailwind CSS / MUI – responsive and modern UI design
* Vite – build tool for optimized performance

### Backend

* Spring Boot – RESTful API framework
* Spring Security – authentication and authorization
* Spring Data JPA (Hibernate) – ORM and database handling
* MySQL – relational database
* Razorpay API – payment gateway integration

---

## Features

* User registration and authentication
* Product browsing with filtering and sorting
* Shopping cart management
* Secure checkout using Razorpay payment gateway
* Order tracking and order history
* Admin dashboard for managing products, categories, and orders
* Email notifications for user and order updates

---

## Installation and Setup

### Backend (Spring Boot)

1. Open the backend project in **IntelliJ IDEA**.
2. Update `application.properties` with:

   * Database name, username, and password
   * Razorpay API key and secret
   * Gmail address and app password for email notifications
3. Create a MySQL database:

   ```sql
   CREATE DATABASE ecommerce;
   ```
4. Run the main Spring Boot application class.
5. The backend will start on **[http://localhost:5454](http://localhost:5454)**

### Frontend (React)

1. Open the frontend folder in **VS Code**.
2. Install dependencies:

   ```bash
   npm install
   ```
3. Create a `.env` file in the project root and add:

   ```
   VITE_API_BASE_URL=http://localhost:5454
   VITE_RAZORPAY_KEY=your_razorpay_test_key
   ```
4. Start the development server:

   ```bash
   npm run dev
   ```
5. Open the application in your browser at **[http://localhost:5173](http://localhost:5173)**

---

## Usage

1. Register as a new user and log in.
2. Browse available products and view details.
3. Add items to the cart and adjust quantities as needed.
4. Proceed to checkout and complete the payment using Razorpay.
5. View order history and track order status.
6. Admin users can log in to manage products and orders.

---

## API Documentation

All REST API endpoints are documented and can be accessed through Swagger UI:
**[http://localhost:5454/swagger-ui/index.html](http://localhost:5454/swagger-ui/index.html)**

---

## Author

**Adil Talukdar**
Email: [adil.talukdar12j@gmail.com](mailto:adil.talukdar12j@gmail.com)
LinkedIn: [https://www.linkedin.com/in/adiltalukdar/](https://www.linkedin.com/in/adiltalukdar/)

---


## About the Project

This e-commerce platform was developed as a complete full-stack solution integrating a **React-based frontend** with a **Spring Boot REST API backend**.
It demonstrates proficiency in frontend and backend integration, database design, secure authentication, and payment gateway integration for real-world web applications.

