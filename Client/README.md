
# 🛍️ AshoperPoint – Full-Stack E-Commerce Store

AshoperPoint is a full-stack e-commerce web application designed for selling clothing, footwear, watches, and fashion accessories. It provides a seamless shopping experience with secure authentication, dynamic product listings, cart management, order tracking, and order history.

The application uses modern frontend and backend technologies to deliver a responsive, scalable, and user-friendly shopping platform.

## ✨ Features

- **Dynamic Product Listings:** Product information, pricing, categories, and other details are fetched dynamically through APIs.
- **User Authentication:** Secure login and registration using JWT (JSON Web Token) authentication.
- **Login & Logout:** Manage user sessions and access protected features.
- **Shopping Cart:** Add products to the cart and manage cart items.
- **Order Management:** Place orders and view previous orders.
- **Order Tracking:** Track order status and monitor order progress.
- **Order History:** Access previously placed orders and their details.
- **Fashion Categories:** Browse a wide range of clothing, footwear, and accessories.
- **Responsive UI:** Responsive layouts built with Tailwind CSS for different screen sizes.
- **API Integration:** Communicate with backend services through REST APIs.
- **State Management:** Redux Toolkit and RTK Query for application state management, API requests, and caching.
- **Database Integration:** MongoDB for storing application data.
- **Protected Routes:** Restrict access to authorized pages and user-specific features.

## 👕 Product Categories

AshoperPoint includes a variety of fashion products, such as:

- Pants and Trousers
- Shirts and T-Shirts
- Kurtis
- Jeans
- Hoodies
- Sports Shirts
- Watches
- Shoes
- Fashion Accessories

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- RTK Query
- Tailwind CSS
- JavaScript (ES6+)
- HTML5
- CSS3

### Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication

### Database
- MongoDB

### Tools & Development
- Git
- GitHub
- Visual Studio Code
- npm

## 🏗️ Application Architecture

The application follows a full-stack architecture:

1. **Frontend:** React.js provides the user interface and interactive shopping experience.
2. **State Management:** Redux Toolkit manages application state, while RTK Query handles API communication and caching.
3. **Backend:** Node.js and Express.js process API requests and implement server-side logic.
4. **Authentication:** JWT-based authentication secures user-specific operations and protected resources.
5. **Database:** MongoDB stores product, user, and order data.
6. **Data Flow:** The frontend communicates with backend REST APIs to retrieve product information, authenticate users, manage cart operations, and access order details.

## 🔐 Authentication & Security

- JWT-based user authentication.
- Protected API endpoints for authorized operations.
- Secure handling of user-specific order information.
- Authentication middleware for validating requests.
- Login and logout functionality.

**Note:** Sensitive credentials and JWT secrets should be stored in environment variables and should never be committed to the repository.

## 🛒 Shopping Workflow

1. Users browse available products and categories.
2. Users register or log in to their accounts.
3. Users add products to their shopping cart.
4. Users proceed through the order placement process.
5. Users view their previous orders.
6. Users track order status and progress.

## 📁 Project Structure

The project may be organized into separate frontend and backend directories:

```text
AshoperPoint/
├── client/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── features/
│       ├── services/
│       ├── app/
│       ├── hooks/
│       └── assets/
│
├── server/
│   |── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── .gitignore
└── README.md
```



## ⚙️ Installation & Setup

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm
- MongoDB (local installation or a MongoDB Atlas database)

### 1. Clone the Repository

```bash
git clone https://github.com/ritik-bg/ashoperpoint.git
cd AshoperPoint
```

### 2. Install Frontend Dependencies

```bash
cd client
npm install
```

### 3. Install Backend Dependencies

Open another terminal:

```bash
cd server
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the backend directory and configure the required variables:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_jwt_secret
```

Configure the frontend API base URL according to your application's setup.

**Important:** Never share or commit your real database credentials or JWT secret.

### 5. Start the Backend

```bash
cd server
npm run dev
```

Use the appropriate script configured in your backend `package.json`.

### 6. Start the Frontend

```bash
cd client
npm run dev
```

Open the local URL displayed by Vite or your configured development server.

## 🚀 Future Improvements

- Wishlist functionality.
- Product search, sorting, and filtering.
- Product reviews and ratings.
- Payment gateway integration.
- Admin dashboard for product and order management.
- Email notifications for order updates.
- Improved product recommendations.

## 🎯 Project Objective

The main objective of AshoperPoint is to build a complete e-commerce platform while applying practical full-stack development concepts, including React component architecture, API integration, Redux state management, secure authentication, database operations, and order management.

## 👨‍💻 Developer

Developed as a full-stack e-commerce project using modern JavaScript technologies.

---

⭐ If you find this project useful, consider giving the repository a star!
