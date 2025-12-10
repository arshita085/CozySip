# 🍹 CozySip – Online Beverage Ordering Platform

CozySip is a full-stack online beverage ordering web application built using **Django**, designed to provide a smooth and user-friendly online ordering experience for beverages like coffee, matcha, juices, and more.  
It includes features like real-time cart updates, secure authentication, product browsing, and a custom admin dashboard.

---

## 🚀 Features

### 🌟 User Side
- Fully responsive UI built with **HTML, CSS, Bootstrap**
- User Registration, Login & Logout (Django Auth)
- Browse beverages by **category & sub-category**
- Search and filter products
- Real-time cart management
- Quantity increase/decrease in cart
- Secure checkout system
- Product details page with description & price
- Smooth animations and custom branding

### 🛠 Admin Side
- Add / Edit / Delete products
- Manage categories & sub-categories
- Order management
- Image upload using Django admin with media support
- Custom admin interface for better usability

---

## 🏗 Tech Stack

| Component | Technology |
|----------|------------|
| Backend  | Django, Python |
| Frontend | HTML, CSS, Bootstrap, JavaScript |
| Database | SQLite |
| Tools    | VS Code, Git, GitHub |
| Media Handling | Django Media Storage |

---

## 📁 Project Structure

```
CozySip/
├── myproject/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
├── myapp/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   ├── static/
│   ├── migrations/
│   └── admin.py
├── media/
├── db.sqlite3
├── manage.py
└── README.md
```

---

## 📦 Installation & Setup (Local Machine)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/CozySip.git
cd CozySip
```

### 2️⃣ Create virtual environment
```bash
python -m venv venv
venv\Scripts\activate    # Windows
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Apply migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run the server
```bash
python manage.py runserver
```

Visit:
```
http://127.0.0.1:8000/
```

---

## 🛠 Admin Panel

Create admin user:
```bash
python manage.py createsuperuser
```

Admin login:
```
http://127.0.0.1:8000/admin
```

---


## 🤝 Contribution
Pull requests are welcome!  
Feel free to open an issue for improvements or bugs.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 👩‍💻 Developed By  
**Arshita Bhikhadiya**  
Python | Django Developer  
GitHub: arshita085  
Email: arshitabhikadiya08@gmail.com

