# 🏀 NBA Stats Web App

This project is bootstrapped with **Create React App**, **Express**, and **MongoDB Atlas**.

---

## ⚡ Quick Start

### 1. Install Dependencies
```bash
npm install
```

### 2. Run the Application
In the project directory, run:
```bash
npm start
```
This concurrently starts:
- **Frontend App**: [http://localhost:7070](http://localhost:7070)
- **Backend API**: [http://localhost:5050](http://localhost:5050)

Open [http://localhost:7070](http://localhost:7070) in your browser to view the application!

---

## 🛠 Available Scripts

| Command | Description |
| :--- | :--- |
| `npm start` | Runs both backend API (port 5050) and React frontend (port 7070) concurrently |
| `npm run client` | Runs the React frontend development server only (port 7070) |
| `npm run server` | Runs the Express MongoDB API server only (port 5050) |
| `npm run build` | Builds the React frontend for production |
| `npm test` | Runs the React test runner |

---

## 💾 Database Configuration

The MongoDB Atlas connection is configured in `.env`:
```env
PORT=7070
API_PORT=5050
MONGODB_URI=mongodb+srv://...
```

If the live MongoDB cluster is ever unreachable or offline, the server automatically runs in **fallback mode** using sample NBA game logs so the app remains viewable at all times.