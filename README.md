# 👜 Bag Project

A full-stack **Node.js + Express** web application for managing an online bag store with features like product listing, cart system, and authentication.

---

## 🚀 Features

* 🛍️ Browse products (bags)
* ➕ Add to cart
* ➖ Remove from cart
* 🔐 User authentication (login/logout)
* 🧑‍💼 Admin panel for managing products
* 🎨 Dynamic UI using EJS templates

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Frontend:** EJS, HTML, CSS
* **Database:** MongoDB (assumed from structure)
* **Other:** Multer (for file uploads), JWT (auth)

---

## 📁 Project Structure

```
Bag-project/
│── config/              # App configuration
│── controllers/         # Business logic
│── middlewares/         # Auth & other middleware
│── routes/              # Express routes
│── utils/               # Helper functions
│── public/              # Static files (images, CSS)
│── views/               # EJS templates
│── app.js               # Main server file
│── package.json         # Dependencies
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/fabrohit03/Bag-project.git
cd Bag-project
```

### 2. Install dependencies

```bash
npm install
```

### 3. Setup environment variables

Create a `.env` file in root and add:

```
PORT=3000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

### 4. Run the project

```bash
npm start
```

---

## 🌐 Usage

* Open browser and go to:
  👉 `(https://bag-project.onrender.com)`

---

## 📸 Screenshots

*Add screenshots of your project here (optional but recommended)*

---

## 👨‍💻 Author

**Rohit Chandel**

* GitHub: https://github.com/fabrohit03

---

## ⭐ Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---
