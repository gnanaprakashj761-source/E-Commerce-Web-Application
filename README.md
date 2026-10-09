# E-Commerce-Web-Application
# ecommerce-web-application
# ShopEasy — E-Commerce Web Application

A full-stack online store with product management and order tracking, built as an internship project for Thiranex.

## Features
- Product catalog, add to cart, and checkout
- User registration and login with role-based access (Admin / User)
- Secure authentication using JWT and bcrypt-hashed passwords
- Backend REST APIs for product and order management
- MongoDB database integration using Mongoose
- Admin dashboard: add, edit and delete products, view all orders, update order status
- Server-side price calculation and stock updates at checkout

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Auth:** JSON Web Tokens (JWT), bcryptjs

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- MongoDB (local install) or a free MongoDB Atlas cluster

### Installation
1. Clone this repository
   `git clone https://github.com/Janarthanan-8/ecommerce-app.git`
2. Go into the folder and install dependencies
   `cd ecommerce-app`
   `npm install`
3. Copy `.env.example` to `.env` and set your values
   `MONGO_URI=your_mongodb_connection_string`
   `JWT_SECRET=your_secret_key`
4. Start the server
   `npm start`
5. Open `http://localhost:3000` in your browser

### Default Admin Account
On first run the app creates sample products and an admin account:
- Email: `admin@shop.com`
- Password: `admin123`

Change this password before deploying.

## API Endpoints
| Method | Endpoint | Access |
|---|---|---|
| POST | /api/auth/register | Public |
| POST | /api/auth/login | Public |
| GET | /api/products | Public |
| POST | /api/products | Admin |
| PUT | /api/products/:id | Admin |
| DELETE | /api/products/:id | Admin |
## Project Structure

## Live Demo
 https://gnanaprakashj761-source.github.io/E-Commerce-Web-Application/

## Learning Outcomes
Hands-on experience building a complex full-stack application with real-world features: authentication, role-based access, REST APIs, database integration, and order management.
