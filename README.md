# AgroX# 🌾 AgroX – Farmer-to-Buyer Digital Marketplace

AgroX is a full-stack production-grade marketplace connecting farmers directly with buyers, eliminating middlemen and improving agricultural trade transparency. The platform supports crop listing, online payments, live order tracking, and automated notifications.

---

## 🚀 Tech Stack

### Frontend
- React
- Tailwind CSS
- Axios
- JWT Authentication

### Backend (Microservices)
- Spring Boot
- Spring Security + JWT
- Spring Cloud API Gateway
- Eureka Service Registry
- MySQL
- Redis Cache
- Razorpay Payment API

### DevOps & Deployment
- Docker Containers
- AWS EC2 for Backend
- AWS S3 for Image Storage
- GitHub Actions (CI/CD)
- Vercel for Frontend Hosting

---

## 🧩 Microservices Architecture

| Service | Responsibility |
|--------|----------------|
| **Auth Service** | Login, Registration, JWT, Roles (Farmer / Buyer / Admin) |
| **Product Service** | Crop listings, search, categories, images |
| **Order Service** | Cart, Orders, delivery tracking |
| **Payment Service** | Razorpay integration, webhooks, invoices |
| **Notification Service** | Email + System notifications |
| **API Gateway** | Entry point for all frontend requests |

---

## 🔐 User Roles
- 👨‍🌾 **Farmer** — Upload products, manage stock, view orders
- 🛒 **Buyer** — Explore products, purchase, track orders
- 🛡 **Admin** — Approve farmers, resolve disputes, monitor activity

---

## 🌟 Key Features
- JWT secure login for all three roles
- Online payments with Razorpay
- Automatic PDF invoice generation & email notifications
- Redis caching to speed up product search
- Microservices communication using Spring Cloud
- Horizontally scalable architecture

---

## 📦 Folder Structure

