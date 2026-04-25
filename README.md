# 🚀 Express EJS MongoDB CRUD App

A simple and clean **CRUD (Create, Read, Update, Delete)** web application built using **Node.js**, **Express.js**, **EJS**, **MongoDB**, and **Tailwind CSS**.

This project allows users to:

* ➕ Create a new user
* 📖 View all users
* ✏️ Edit existing users
* ❌ Delete users

---

## 📌 Features

* ✅ Create User Form
* ✅ Read All Users
* ✅ Update User Details
* ✅ Delete User
* ✅ MongoDB Integration with Mongoose
* ✅ Server-side rendering using EJS
* ✅ Tailwind CSS UI Styling
* ✅ Clean and beginner-friendly project structure

---

## 🛠️ Tech Stack

* **Node.js**
* **Express.js**
* **EJS**
* **MongoDB**
* **Mongoose**
* **Tailwind CSS**

---

## 📂 Project Structure

```bash
express-ejs-mongodb-crud/
│── models/
│   └── user.js
│── public/
│   └── stylesheets/
│       ├── input.css
│       └── output.css
│── views/
│   ├── index.ejs
│   ├── read.ejs
│   └── edit.ejs
│── .gitignore
│── app.js
│── package.json
│── package-lock.json
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yuvi558/express-ejs-mongodb-crud.git
cd express-ejs-mongodb-crud
```

> ⚠️ Replace the repo URL with your actual GitHub repository URL if different.

---

### 2️⃣ Install dependencies

```bash
npm install
```

---

### 3️⃣ Make sure MongoDB is running

This project uses local MongoDB connection:

```js
mongodb://127.0.0.1:27017/testapp1
```

So make sure:

* MongoDB is installed
* MongoDB service is running on your system

---

### 4️⃣ Run the server

```bash
node app.js
```

Server will run on:

```bash
http://localhost:3000
```

---

## 🎨 Tailwind CSS Setup

If you are using Tailwind CSS v4, run this command in a separate terminal:

```bash
npx @tailwindcss/cli -i ./public/stylesheets/input.css -o ./public/stylesheets/output.css --watch
```

---

## 🌐 Routes

| Method | Route         | Description               |
| ------ | ------------- | ------------------------- |
| GET    | `/`           | Show Create User form     |
| POST   | `/create`     | Create a new user         |
| GET    | `/read`       | Display all users         |
| GET    | `/edit/:id`   | Open edit form for a user |
| POST   | `/update/:id` | Update user details       |
| GET    | `/delete/:id` | Delete a user             |

---

## 🧠 MongoDB Model

The user model contains:

* `name`
* `email`
* `image`

---

## 📸 Screenshots

You can add screenshots here later:

* Home Page (Create User Form)
* Read Users Page
* Edit User Page

Example:

```md
![Home Page](./screenshots/home.png)
![Read Users](./screenshots/read.png)
![Edit User](./screenshots/edit.png)
```

---

## 📝 Example User Data

* **Name:** Yuvraj Singh
* **Email:** [yuvraj@mail.com](mailto:yuvraj@mail.com)
* **Image URL:** Any valid image link

---

## 🚀 Future Improvements

* 🔐 Form validation
* ⚠️ Error handling with try/catch
* 🖼️ Default image fallback
* 🎉 Flash success/error messages
* 🌍 Use `.env` for MongoDB URI
* ☁️ Deploy on Render / Railway / Vercel (frontend + backend setup)

---

## 📦 .gitignore

```gitignore
node_modules
.env
```

---

## 👨‍💻 Author

**Yuvraj**
GitHub: [@yuvi558](https://github.com/yuvi558)

---

## ⭐ Support

If you like this project, give it a **star ⭐** on GitHub.

---

## 📜 License

This project is open source and available under the **MIT License**.
