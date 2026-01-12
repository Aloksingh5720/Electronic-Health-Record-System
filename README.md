# 🏥 Electronic Health Record (EHR) Management System

> A secure, scalable, and role-based Electronic Health Record system built to digitize and manage patient healthcare data efficiently.

---

## 📌 Project Overview

The **Electronic Health Record (EHR) Management System** is a web-based application designed to help hospitals and clinics manage patient records digitally.  
It replaces manual paperwork with a centralized, secure, and easily accessible system for doctors, patients, and administrators.

This project focuses on **data security, role-based access, and real-world healthcare workflows**.

---

## 🎯 Key Objectives

- Digitize patient medical records
- Improve data accessibility for healthcare providers
- Ensure security and privacy of sensitive health data
- Reduce manual errors and paperwork
- Provide role-based access to users

---

## 🧑‍⚕️ User Roles

- **Admin**
  - Manage doctors and system users
  - Control system configurations

- **Doctor**
  - View assigned patient records
  - Add diagnosis, prescriptions, and reports

- **Patient**
  - View personal medical history
  - Access prescriptions and reports

---

## 🚀 Features

- 🔐 Secure authentication & authorization
- 🏥 Patient record management
- 📄 Medical history tracking
- 💊 Prescription management
- 🧪 Test reports & diagnosis storage
- 🕒 Audit-friendly record updates
- 📊 Scalable backend architecture

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- REST APIs

### Database
- MySQL / PostgreSQL

### Frontend
- HTML
- CSS
- JavaScript
- (Planned: React)

### Tools & Others
- Maven
- Git & GitHub
- Postman

---

## 🏗️ System Architecture

*(High-level overview of system design)*

- Client (Web UI)
- REST API Layer
- Service Layer
- Data Access Layer
- Database

---

## 📸 Screenshots

> *(Add images here later)*

### 🔐 Login Page
![Login Page](screenshots/login.png)

### 🧑‍⚕️ Doctor Dashboard
![Doctor Dashboard](screenshots/doctor-dashboard.png)

### 🧑 Patient Dashboard
![Patient Dashboard](screenshots/patient-dashboard.png)

---

## ⚙️ Installation & Setup

### Prerequisites
- Java 17+
- Maven
- MySQL
- Git

### Steps
```bash
git clone https://github.com/your-username/Electronic-Health-Record-System.git
cd Electronic-Health-Record-System
mvn clean install
mvn spring-boot:run
