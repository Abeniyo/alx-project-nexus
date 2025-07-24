# Smart Pharmacy System for Ethiopia — *MedNearby*

> 📦 A modern, scalable, and intelligent pharmacy ordering and discovery platform built for Ethiopian communities.

---

## 📌 Project Overview

**MedNearby** is a Smart Pharmacy System tailored for Ethiopia, enabling users to search for nearby pharmacies, browse available medicines, compare prices, and place orders online. It bridges the gap between patients and local pharmacies through geolocation and real-time stock visibility.

This project was developed as part of the **ALX ProDev Backend Engineering Program**, showcasing backend best practices, APIs, and systems integration in a real-world healthcare context.

---

## 🎯 Project Objectives

- Build a RESTful API using Django to manage pharmacy listings, medicine catalogs, orders, and user profiles.
- Integrate real-time search and geolocation to help users find nearby medicines.
- Enable digital ordering and payment features across multiple pharmacies.
- Showcase backend engineering best practices, including:
  - Authentication & Authorization
  - Asynchronous tasks with Celery
  - CI/CD pipelines
  - Clean architecture and modular design

---

## 🛠️ Key Technologies & Tools

- **Python & Django**
- **Django REST Framework (DRF)**
- **PostgreSQL/MySQL**
- **Celery + RabbitMQ** (Background task processing)
- **Docker & Docker Compose**
- **Nginx + Gunicorn** (Production deployment)
- **GitHub Actions** (CI/CD)
- **GeoDjango** (for location-based pharmacy search)
- **Stripe / Chapa API** (for payment integration)

---

## 🔍 Features

- 🧭 **Nearby Pharmacy Locator**: Search pharmacies based on your current location.
- 💊 **Medicine Availability**: Check real-time availability of medications.
- 🛒 **Cart & Checkout**: Add medicines to cart and order online.
- 💰 **Secure Payments**: Integrated with Chapa or Stripe for seamless payments.
- 📦 **Order Tracking**: Users can track the status of their orders.
- 🏥 **Multi-pharmacy Support**: System handles multiple pharmacy branches and stocks.

---

## 💡 Key Backend Learnings

### 📘 Concepts

- **RESTful API design**
- **Database schema design & normalization**
- **Token-based Authentication (JWT)**
- **Permission and Role-based Access Control**
- **Asynchronous processing with Celery**
- **Caching strategies using Redis**
- **API documentation using Swagger/OpenAPI**

### ⚙️ Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Handling large datasets of medicines and pharmacy stock | Used efficient querying, indexing, and pagination |
| Real-time location-based search | Integrated GeoDjango with optimized spatial queries |
| Processing payments securely | Used Chapa API sandbox/test mode for integration testing |
| Scaling task queues | Deployed Celery with RabbitMQ and monitored with Flower |

---

## 📋 Best Practices Followed

- ✅ Modular Django architecture (apps: users, pharmacies, orders, payments)
- ✅ `.env` environment variables managed with `django-environ`
- ✅ API versioning and namespacing
- ✅ Dockerized for consistent dev/prod environments
- ✅ GitHub Actions for automated testing and deployment

---

## 🤝 Collaboration

This backend system is designed to be consumed by **Frontend Learners** working on the same project.

- **Discord Collaboration Channel:** `#ProDevProjectNexus`
- **API Documentation:** Auto-generated Swagger/OpenAPI at `/api/docs/`
- **Live API Base URL (Example):** `https://mednearby.et/api/v1/`

---

## 📁 Project Structure

