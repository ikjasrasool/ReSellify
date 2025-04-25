

# 🛒 ReSellify - Local Marketplace Platform

A dynamic and user-friendly web platform for buying and selling pre-owned goods. Designed for **students, communities, and general users**, this app makes reselling efficient, secure, and seamless.

---

## ✨ Overview

**Object Resell App** is a full-stack marketplace where users can:
- Post used items for sale 📤
- Browse and purchase listed products 🛍️
- Search and filter items 🔍
- Manage their listings easily 🧾

Built using **Flask**, **MySQL**, and **Bootstrap**, this app offers a clean, responsive interface optimized for both mobile and desktop usage.

---

## 🚀 Key Features

- 📤 **List Items for Sale** – Post your used items with detailed descriptions and images.
- 🛒 **Buy Used Products** – Browse active listings and connect with sellers directly.
- 🔍 **Search & Filter** – Easily find items using keywords, category, or price filters.
- 👤 **User Authentication** – Secure login/signup using Flask sessions and hashed passwords.
- 🧾 **Product History** – Track user interactions and previous listings.
- ✏️ **Edit/Delete Listings** – Full control over your posted items.
- 📞 **Contact Seller Info** – View the seller’s contact information on each product detail page.
- 📱 **Responsive Design** – Works smoothly on all devices.
- 📊 **Dashboard View** – Personalized dashboard for managing your items and profile.
- 🛠️ **Admin Panel (Upcoming)** – Add, review, and moderate listings site-wide.

---

## 🛠️ Tech Stack

| Component         | Technology                            |
|------------------|----------------------------------------|
| Backend           | `Flask (Python)`                      |
| Frontend          | `HTML`, `CSS`, `JavaScript`, `Bootstrap` |
| Database          | `MySQL`                               |
| Authentication    | `Flask-Login`                         |
| Templating Engine | `Jinja2`                              |
| Version Control   | `Git`, `GitHub`                       |

---

## ⚙️ Getting Started

### 💻 Clone the Repository

```bash
git clone https://github.com/ikjasrasool/reselling_fullstack_project.git
cd reselling_fullstack_project
```

### 📦 Set Up Environment

Install Python packages:
```bash
pip install flask flask-mysqldb werkzeug
```

> ✅ Make sure MySQL is installed and running.

### 🛠️ Configure the Database

1. Create a MySQL database (e.g., `resell_db`).
2. Update `app.py` with your database credentials:
```python
app.config['MYSQL_HOST'] = 'localhost'
app.config['MYSQL_USER'] = 'your_username'
app.config['MYSQL_PASSWORD'] = 'your_password'
app.config['MYSQL_DB'] = 'resell_db'
```
3. Import the schema using your MySQL tool or via terminal.

### ▶️ Run the Application

```bash
python app.py
```

Visit: [http://localhost:5000](http://localhost:5000)

---

## 📂 Project Structure

```bash
reselling_fullstack_project/
├── static/
│   ├── css/
│   └── images/
├── templates/
│   ├── homr.html
│   ├── login.html
│   ├── register.html
│   └── ...
├── app.py
├── requirements.txt
└── README.md
```

---

## 📌 Future Enhancements

- 🧠 Smart search with AI-based recommendations.
- 📧 Email notifications for buyer-seller communication.
- 📦 Product categories and subcategories.
- 📊 Admin dashboard with analytics.
- 📱 PWA support for mobile-like experience.

---

## 🤝 Contributing

We 💙 community contributions!

1. Fork the repo
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Create a Pull Request 🚀

---
