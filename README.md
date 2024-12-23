# Cartopia

## 🚀 Project Setup
This project is a full-featured e-commerce platform designed to provide a seamless shopping experience for users while enabling administrators to efficiently manage products, sales, and analytics.

## Features

### 🗄️ MongoDB & Redis Integration
- **MongoDB**: Used as the primary database for storing user data, product information, orders, and more.
- **Redis**: Integrated for caching frequently accessed data to improve performance and reduce latency.

### 💳 Stripe Payment Setup
- Implemented **Stripe** to handle secure and reliable payment transactions.
- Supports various payment methods for a smooth checkout experience.

### 🔐 Robust Authentication System
- User authentication is implemented using **JSON Web Tokens (JWT)**.
- Both access and refresh tokens are used for secure and scalable user session management.

### 📝 User Signup & Login
- Users can register and log in to access personalized features like shopping carts, order history, and more.

### 🛒 E-Commerce Core
- The platform includes all essential e-commerce features:
  - Product browsing and search.
  - Category filtering and management.
  - Easy navigation through products and categories.

### 📦 Product & Category Management
- Allows administrators to:
  - Add, update, and delete products.
  - Organize products into categories.

### 🛍️ Shopping Cart Functionality
- Users can add products to their shopping cart.
- Supports multiple items with quantity adjustments.

### 💰 Checkout with Stripe
- A seamless checkout process integrated with **Stripe** for secure payment handling.

### 🏷️ Coupon Code System
- Users can apply discount codes during checkout.
- Administrators can create and manage coupon codes.

### 👑 Admin Dashboard
- Comprehensive dashboard for administrators to:
  - Manage products, categories, and orders.
  - Monitor user activity.

### 📊 Sales Analytics
- Visualize sales performance with detailed analytics.
- Track revenue, popular products, and user trends.

### 🎨 Design with Tailwind
- A modern, responsive user interface designed with **Tailwind CSS**.
- Ensures a consistent and attractive design across devices.

### 🔒 Security
- Implements best practices to ensure the security of user data.
- Protects sensitive information, including passwords and payment details.

### 🛡️ Data Protection
- Secure handling of user data with encryption and compliance with data protection standards.

### 🚀 Caching with Redis
- Optimizes performance by caching frequently accessed data using **Redis**.
- Reduces database load and speeds up page loading times.

## 🛠️ Technologies Used
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Redis
- **Payments**: Stripe
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Render

## 📄 How to Run
1. Clone the repository.
2. Install dependencies using `npm install`.
3. Set up environment variables for MongoDB, Redis, and Stripe.
4. Run the backend server: `npm start`.
5. Access the application in your browser at `http://localhost:3000`.

## 📖 License
This project is licensed under the MIT License.
