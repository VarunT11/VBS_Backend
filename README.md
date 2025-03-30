# 🔗 SlotSync Backend: Django REST API for IIITA Venue Booking System

This repository contains the backend service for **SlotSync**, a role-based venue booking and approval system developed for IIIT Allahabad. The backend powers the Android app by managing authentication, bookings, venue data, and a multi-level approval workflow.

---

## 🔍 Overview

SlotSync Backend is built using **Django** and **Django REST Framework**, exposing RESTful APIs that handle:
- User authentication (Google OAuth)
- Role-based access control
- Booking creation, editing, and tracking
- Multi-level approvals (Faculty → Dean → Admin)
- Venue and user management

---

## ✨ Features

- 🔑 Google OAuth integration for IIITA domain users
- 📆 Support for one-time and recurring bookings
- ⚖️ Multi-step approval logic with status tracking
- 🔎 Role-based permissions: User, Authority, Admin
- 🔢 Admin APIs for adding/updating venues and users
- 📊 Modular app structure for scalability and maintenance

---

## 🛠️ Tech Stack

- **Framework:** Django
- **API:** Django REST Framework (DRF)
- **Authentication:** Google OAuth 2.0 (Firebase / custom integration)
- **Database:** SQLite (for internal deployment; portable to PostgreSQL)
- **Deployment:** Configurable via environment settings

---

## 📖 Use Case: IIIT Allahabad

- Built to support **100+ campus venues** across labs, auditoriums, and classrooms
- Scales to handle bookings and approval workflows for **3,000+ users** (students & faculty)
- Reduced approval time for key venues (e.g., Auditorium) from **1–2 days to a few hours**

---

## 📓 Related Repositories
- 📱 [Android App (Frontend)](https://github.com/VarunT11/Venue-Booking-System)

---

## 👤 Author

**Varun Tiwari**  
[GitHub](https://github.com/VarunT11) | [LinkedIn](https://linkedin.com/in/iamvt11)

---

## ✉️ License

This project was developed as part of an institutional initiative at IIITA and is not currently open to public contributions.
