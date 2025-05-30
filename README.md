# book-analytics-backend
A lightweight Node.js and Express backend for logging user activity (clicks, searches, and more) in real time, built for book analytics dashboards.
# 🔍 Realtime Logging Server (Node.js + Express)

This project is a lightweight backend logging server built with **Node.js**, **Express**, and **Nodemon**. It receives log data from the frontend (e.g., search queries, user actions) and stores them in a text file for later analysis.

---

### 🚀 Features

- Accepts `POST` requests at `/log`
- Saves logs to `activity-log.txt`
- Uses `Nodemon` for automatic server restarts
- CORS enabled for frontend integration

---

### 📦 Installation

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
npm install
