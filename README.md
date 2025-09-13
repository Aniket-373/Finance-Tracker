# 💰 Personal Finance Tracker

A **Personal Finance Tracker** web application built with the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** and styled using **Tailwind CSS**.  
This app helps users manage their incomes and expenses, visualize financial data with charts, and maintain a clean and user-friendly interface.

---

## 🚀 Features

- ✅ User Authentication (Signup & Login)
- ✅ Add, View, Edit, and Delete Income & Expense entries
- ✅ Visualize financial data with dynamic charts
- ✅ Emoji-based category selection for fun and intuitive interaction
- ✅ Persistent storage using localStorage
- ✅ Clean & modern UI with Tailwind CSS
- ✅ Responsive design for mobile and desktop
- ✅ Download Income & Expense reports
- ✅ Confirmation modals for adding & deleting records

---

## 📊 Charts

- Donut & Bar charts to visualize income and expenses over time  
- Helps track total income vs total expense in the last 30/60 days  
- Interactive and easy to understand

---

## 🛠 Tech Stack

| Frontend | Backend | Database | Styling |
|----------|---------|----------|---------|
| React.js | Express.js | MongoDB | Tailwind CSS |
| Axios for HTTP requests | Node.js | Mongoose ODM | react-hot-toast for notifications |
| react-icons for icons | JWT for Authentication | LocalStorage for caching |

---

## ⚡ Usage

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aniket-373/Finance-Tracker.git
    cd Finance-Tracker
    ```

2. Install dependencies for frontend and backend:
    ```bash
    cd client
    npm install
    cd ../server
    npm install
    ```

3. Setup environment variables:
    Create a `.env` file in the server folder with:
    ```env
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    CLIENT_URL=http://localhost:5173
    ```

4. Start the development servers:
    - Backend (Node.js + Express):  
      ```bash
      npm run dev
      ```

    - Frontend (React + Vite):  
      ```bash
      npm run dev
      ```

---

## 🎯 Sample Screenshots

![App Screenshot](./path-to-your-screenshot.png)  
_Example of Income Overview and Dashboard Chart_

---

## ✅ Why Use This App?

- Simple, intuitive interface built for managing personal finances  
- Fast performance with Vite and MongoDB  
- Charts help you easily understand your financial patterns  
- Easy emoji-based category input for expenses and income  
- Fully responsive and mobile-friendly

---

## 🧱 Project Structure

plaintext
client/                # Frontend (React)
server/                # Backend (Node.js + Express)
components/            # Reusable UI components (IncomeList, Modals, Forms, etc.)
utils/                 # API utilities, Axios instance, helper functions
models/                # MongoDB models
routes/                # Express route handlers
middleware/            # Authentication middlewares
.env                   # Environment variables

```

## 📚 Future Enhancements

- Multi-user support with real-time collaboration
- Export reports in PDF or Excel format
- Advanced charts with filters (time range, categories)
- Push notifications for budget limits

```

## 📞 Contact

```👤 Created by Aniket Bhoir
📧 Email: aniket@example.com
🔗 GitHub Profile
```

## ⭐️ Support

- If you find this project useful, feel free to ⭐️ the repo!
- Made with ❤️ MERN + Tailwind CSS

```
