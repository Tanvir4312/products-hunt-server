# 🚀 Product Hunt Server

A REST API backend for the Product Hunt platform handling authentication, product moderation, reviews, and payment processing.

---

## 📖 About The Project

Product Hunt backend manages the entire platform — from user authentication and product submissions to moderation workflows, review systems, and secure payment processing via Stripe.

---

## 🛠️ Tech Stack

- JavaScript
- Node.js
- Express.js
- MongoDB
- Firebase (Authentication)
- Stripe (Payment)

---

## ✨ Key Features

- 🔐 Authentication with Firebase
- 📦 Product submission & management
- ✅ Moderation system for product approval/rejection
- ⭐ Review & rating system
- 👍👎 Like & dislike tracking on reviews
- 💳 Payment processing with Stripe

---

## 📁 Project Structure Highlights

- `index.js` — Main server entry point with all routes & middleware

---

## ⚙️ Setup Instructions

```bash
git clone https://github.com/Tanvir4312/products-hunt-server
cd products-hunt-server
npm install
node index.js
```

---

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```dotenv
DB_USER=product-hunt
DB_PASS=your_DB_PASS
VITE_SECRET_KEY=your_VITE_SECRET_KEY
ACCESS_TOKEN_SECRET=your_ACCESS_TOKEN_SECRET
```

---

## 🔗 Links

- **Frontend Repo:** [products-hunt-client](https://github.com/Tanvir4312/products-hunt-client)
