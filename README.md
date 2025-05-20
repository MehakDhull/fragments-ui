# fragments-ui

# 🧩 Fragments Project — Lab 2

## 📚 Lab 2 Overview

This lab focused on securely connecting a client web application to a protected backend microservice using **Amazon Cognito** for authentication. The core goal was to implement user sign-in via a hosted login UI and secure API access using JWT-based authentication. You configured:

- Amazon Cognito User Pool (authentication provider)
- A Node.js microservice with secure routes (`/v1/fragments`)
- A frontend client (with Parcel) that allows users to log in and fetch protected data using their tokens

Successful login results in a JWT, which is passed in the `Authorization` header for secure API requests.

---

## 📦 Project Structure
cloud-for-porgrammers
/fragments # Backend microservice (Node.js + Express)
/fragments-ui # Frontend web app (Parcel + JS)


---

## 🛠 Setup & Run

### 1. Install Dependencies

```bash
# Backend
cd fragments
npm install

# Frontend
cd ../fragments-ui
npm install

# In /fragments
npm run dev

# In /fragments-ui
npm run dev 
```
