<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/2cffc638-6bfa-465d-b730-5b9d8229edff"
    alt="LifeLink Splash"
    width="220"
  />
</p>

# 🩸 LifeLink – The Digital Bridge Between Donor and Hope

LifeLink is a **health-tech platform** that connects **donors** and **recipients** for **blood, plasma, and organ donations**.  
It uses **location awareness**, **real-time availability**, and a **hybrid AI-based matching system** to reduce emergency response time and improve accessibility.

> 🚧 **Project Status:** Under Active Development

---

## 📌 Problem Statement

During medical emergencies, finding a compatible donor quickly is difficult because:
- Donor availability is not updated in real time
- Matching is mostly manual and slow
- No intelligent prioritization of donors

LifeLink solves this using **automation, AI, and scalable microservices**.

---

## 🎯 Objectives

- Fast and accurate donor–recipient matching
- Reduced emergency response time
- Secure handling of medical and personal data
- Intelligent donor prioritization using ML

---

## 🛠️ Tech Stack

### Frontend
- React Native
- Expo

### Backend
- Spring Boot (Java)
- Microservices Architecture

### Machine Learning (AI Matching Engine)
- Python
- XGBoost Algorithm
- Hybrid Matching Logic:
  - **30% Rule-Based Matching**
  - **70% Machine Learning-Based Prediction**

### Database & Cache
- PostgreSQL
- Redis

### Authentication & Security
- JWT (JSON Web Tokens)
- Spring Security *(Auth Service only)*

### Communication
- REST APIs
- gRPC
- Feign Client
- Spring Cloud Gateway

### Messaging
- Apache Kafka *(Event-driven communication)*

### DevOps & Deployment
- Docker
- ngrok

---

## 🤖 AI-Based Matching Logic

LifeLink uses a **hybrid matching approach**:

### 🔹 Rule-Based Matching (30%)
- Blood group compatibility
- Donation type (blood / plasma / organ)
- Minimum medical eligibility rules
- Location radius filtering

### 🔹 Machine Learning Matching (70%)
- XGBoost model trained using:
  - Donor availability history
  - Distance between donor and recipient
  - Previous successful donations
  - Emergency priority level
- Produces a **matching score**
- Higher score = higher donor priority

This combination ensures **accuracy, fairness, and reliability**.

---

## 📱 Features

- 📍 Location-Based Donor Matching
- 🤖 AI-Powered Smart Matching (XGBoost)
- 🩸 Blood, Plasma, and Organ Donation Support
- 🗂️ Donation History Tracking
- 🔐 OTP Login & JWT Authentication
- 📱 Cross-Platform Mobile App (Expo + React Native)
- 🧠 AI Chatbot *(Planned)*
- 🔁 Event-Driven Microservices (Kafka)
- 🧾 Role-Based Access Control (RBAC)
- 🛡️ Centralized API Gateway

---

## 🧩 System Architecture

- Microservice-based design
- Services:
  - Authentication Service
  - Donor Service
  - Recipient Service
  - Matching Service (ML + Rules)
  - Notification Service
- API Gateway for routing & security
- Kafka for async communication
- Python ML service integrated via REST

---

## 📸 Demo & Presentation

### 🎥 Application Demo  
https://drive.google.com/file/d/1KqJp6bXnV086TV6FVBu25VmF8jhKECK3/view?usp=sharing

### 🎤 Project Presentation  
https://youtu.be/eM6tniPAzJ8?si=-RUSFBi0EMMUBxjw

---
