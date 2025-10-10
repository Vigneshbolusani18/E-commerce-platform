# 🛒 MERN‑Stack E‑Commerce Website

This project is a full-stack e-commerce application built using **React**, **Node.js**, **Express**, and **MongoDB** (MERN stack), with real-world features and deployment on **Vercel**. It supports browsing, filtering, product variants, cart management, checkout with two payment gateways (Stripe and Razorpay), and an admin dashboard for product management.

---

## 💡 Features

- **Product Browsing**: Explore and filter products by category, price, variant (e.g. size).
- **Cart System**: Add products with selected variants to the cart for checkout.
- **Checkout Options**:
  - Cash on Delivery
  - Online Payments via **Stripe** and **Razorpay**
- **Admin Dashboard**:
  - Upload, edit, or delete products
  - View/manage all orders and product inventory
- **Full-Stack Architecture**: React on frontend, Node.js/Express backend, MongoDB database
- **Deployment**: Live deployment via **Vercel**

---

## 🧱 Tech Stack

- **Frontend**: React JS
- **Backend / API**: Node.js + Express
- **Database**: MongoDB (via Mongoose)
- **Payment Gateways**: Stripe and Razorpay
- **Deployment Platform**: Vercel

---

## 📁 Project Structure
```bash
/frontend → Customer-facing React app
/backend → Express backend with APIs and payment integration
/admin → Admin dashboard (React or similar)
```
---
## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mp-lp/ecommerce-app.git
cd ecommerce-app
```
---
### 2. Backend Setup
```bash
cd backend
npm install
```
---
Create a .env file in /backend:
```bash
MONGODB_URI=mongodb+srv://your-username:your-password@cluster.mongodb.net/your-db-name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key
CLOUDINARY_NAME=your_cloudinary_cloud_name
JWT_SECRET=your_jwt_secret_key
ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=your_admin_password
STRIPE_SECRET_KEY=your_stripe_secret_key
RAZORPAY_KEY_SECRET=your_razorpay_secret_key
RAZORPAY_KEY_ID=your_razorpay_key_id
```
Start the backend:
```bash
npm run server
```
---
### 3. Frontend Setup
```bash
cd ../frontend
npm install
npm run dev
```
---
### 4. Admin Setup
```bash
cd ../admin
npm install
npm run dev
```
---
## 🌍 Live Deployment

-**Frontend (Vercel)**: https://ecommerce-app-frontend-drab.vercel.app/

-**Admin Dashboard**: https://ecommerce-app-admin-two.vercel.app/

-**Backend**: Hosted separately or as serverless functions



