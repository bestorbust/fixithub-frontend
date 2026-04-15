# 🚀 FixItHub – Frontend (Angular)

🔗 Live App: https://fix-it-hub-rho.vercel.app/  
🔗 Backend Repo: https://github.com/bestorbust/fixithub-backend  

---

## 📌 Overview

This repository contains the **Angular frontend** for FixItHub, a community issue reporting platform that enables citizens to report and track civic issues in real time.

The frontend provides an interactive UI for both **citizens and authorities**, integrating seamlessly with the Flask backend via REST APIs.

---

## ✨ Features

### 👤 Citizen
- Register & Login (JWT-based)
- Report issues with:
  - 📍 Location (Map API)
  - 🖼️ Image upload
  - 📝 Description
- View, edit, delete, and reopen issues
- Comment and vote on issues

### 🏛️ Authority
- Dashboard with statistics
- Manage users and reported issues
- Update issue status

---

## ⚙️ Tech Stack

- Angular (v19)
- TypeScript
- HTML/CSS + Bootstrap
- REST API integration

---

## 🧠 Architecture Role

Frontend handles:
- UI rendering
- Form validation
- API communication
- Role-based routing

---

## 🧪 Testing

- Angular testing with Karma & Jasmine
- Headless browser testing in CI pipeline

---

## 🚀 Deployment

- Hosted on **Vercel**
- Auto-deployed on every GitHub push

---

## ▶️ Run Locally

```bash
git clone https://github.com/bestorbust/fixithub-frontend.git
cd fixithub-frontend
npm install
ng serve
