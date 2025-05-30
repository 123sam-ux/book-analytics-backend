# 📚 Book Analytics Backend

This is a simple backend logging server built with **Node.js**, **Express**, and **Nodemon**.  
It allows real-time tracking of user activity (like searches or clicks) from a frontend application.
fetch("http://localhost:3000/log", {
  method: "POST",
  headers: {
    "Content-Type": "application/json"
  },
  body: JSON.stringify({
    user: "Samson",
    action: "Searched for a book"
  })
});

---

## 🚀 Features

- Receives POST requests and logs activity
- Saves logs to `activity-log.txt`
- 
---

### ✅ **2. LICENSE Section (MIT)**

Add this at the very end of your `README.md`:

```markdown
## 📝 License

This project is licensed under the MIT License — you are free to use, modify, and distribute this code for personal or commercial use.  
See the [LICENSE](LICENSE) file for full details.

- CORS-enabled and JSON-compatible

---

## 🧰 Tech Stack

- Node.js  
- Express  
- Nodemon

---

## ⚙️ Setup

```bash
git clone https://github.com/your-username/book-analytics-backend.git
cd book-analytics-backend
npm install
nodemon server.js
## 📤 Usage

Once your server is running, you can send log data using a POST request to:


