# 💰 Smart Expense Tracker (with Bank API Integration)

A full-stack expense tracker that helps users **add, edit, delete, and analyze expenses**, with **Plaid API integration** to fetch bank transactions automatically.  
Built with **React (Vite) + Tailwind** for the frontend and **Node.js + Express + MongoDB** for the backend.

---

## 🚀 Features

- 🔑 **User Authentication** – Signup & Login system  
- 📝 **Expense Management** – Add, edit, and delete expenses  
- 📊 **Reports & Analytics** – Get expense reports and summaries  
- 🏦 **Plaid API Integration** – Fetch transactions directly from your bank account  
- 🌐 **Full Stack App** – React (frontend) + Node.js/Express (backend) + MongoDB (database)

---

## 🛠️ Tech Stack

**Frontend**
- React (Vite)
- Tailwind CSS
- Axios

**Backend**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Plaid API

---

## ⚙️ Installation & Setup

```bash
1. Clone Repository
git clone https://github.com/aryanraj71/Smart-Expense-Tracker-using-API.git
cd Smart-Expense-Tracker-using-API

2. Backend
cd backend
npm install

Create a .env file inside backend/ and add:

MONGO_URI=your_mongodb_connection_string
PLAID_CLIENT_ID=your_plaid_client_id
PLAID_SECRET=your_plaid_secret
JWT_SECRET=your_jwt_secret

Start backend:
npm start

3. Frontend Setup
cd frontend
npm install
npm run dev
