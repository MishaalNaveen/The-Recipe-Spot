# 🍽️ The Recipe Spot

**The Recipe Spot** is a community-driven recipe-sharing web application that allows users to post, browse, and interact with culinary content. Authenticated users can publish their own recipes, like and comment on others, and maintain a personalized dashboard.

---

## 📌 Features

- 🔐 User Registration and Login (with session persistence)
- 📝 Create, View, Edit, and Delete Recipes
- 🖼️ Upload recipe images with ingredients, steps, cook time, servings, and calories
- 💬 Comment on and ❤️ Like recipes
- 📊 Personalized user dashboard with activity stats
- 🔍 Search and filter recipes by name, ingredient, or cuisine

---

## 🧑‍💻 Tech Stack

| Layer         | Technology         |
|---------------|--------------------|
| Frontend      | HTML, CSS, JavaScript |
| Backend       | Node.js (Express.js) |
| Database      | SQLite              |


---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/MishaalNaveen/The-Recipe-Spot.git
cd The-Recipe-Spot
```

### Install Dependencies

```bash
npm install
```

### Start the Server

```bash
node server.js
```

Then open `http://localhost:3000` in your browser.

---

## 🗃️ Database

- Database: **SQLite**
- Includes tables for: users, recipes, comments, and likes.

---

## 🔐 Security

- Passwords are securely hashed before storage
- Role-based restrictions on editing/deleting content
- CSRF protection and input validation for all forms
---

