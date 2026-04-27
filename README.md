# 🚀 Django Blog Application – Domebytes

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Django](https://img.shields.io/badge/Django-6.0.3-092E20?style=for-the-badge&logo=django)
![Bootstrap](https://img.shields.io/badge/Bootstrap-4-7952B3?style=for-the-badge&logo=bootstrap)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite)
![PythonAnywhere](https://img.shields.io/badge/Deployed-PythonAnywhere-1D9FD7?style=for-the-badge&logo=pythonanywhere)
![Status](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

# 🚀 Django Blog Application – Domebytes

A full-featured **Django Blog Web Application** built with authentication, role-based dashboards, category management, search functionality, and commenting system.

🔗 **Live Demo:** https://amalaji.pythonanywhere.com/



---

## 📌 Project Overview

This project is a complete blog platform where users can:

* Browse blog posts by category
* Search articles
* Register, login, and interact with content
* Comment on posts
* Manage content via dashboards (Admin/Editor/Manager)

Built using **Django (Full Stack)** following best practices.

---

## ⚙️ Tech Stack

* **Backend:** Django
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** SQLite (default)
* **Authentication:** Django Auth System
* **Deployment:** PythonAnywhere

---

## ✨ Features Implemented

### 🔹 Core Features

* Category-based blog system
* Slug-based SEO-friendly URLs
* Featured & recent posts
* Search functionality
* Custom 404 error page
* Template inheritance

---

### 🔹 Authentication System

* User Registration
* Login & Logout
* Role-based access control
* Django Groups (Editor / Manager)

---

### 🔹 Dashboard System

* Editor Dashboard
* Manager Dashboard
* Role-based permissions
* Sidebar navigation with active states

---

### 🔹 Category Management (CRUD)

* Add Category
* Edit Category
* Delete Category
* Category listing table

---

### 🔹 Blog Management (CRUD)

* Add Blog Post
* Edit Blog Post
* Delete Blog Post
* Assign logged-in user as author
* Unique slug generation

---

### 🔹 Comment System

* Add comments to blog posts
* Display comments
* Only authenticated users can comment

---

### 🔹 Additional Features

* About Us page
* Social links integration
* Context processors for global data
* Media file handling (image uploads)
* Static file management

---

## 🧠 What I Learned (Based on Implementation)

This project was built by implementing concepts step-by-step from a structured tutorial:

### 🟢 Django Fundamentals

* Project & app structure
* Models, Views, Templates (MVT)
* Admin customization

### 🟢 Advanced Django Concepts

* ForeignKey relationships
* Context processors
* Template inheritance
* Custom error handling (404)

### 🟢 Authentication & Authorization

* User authentication system
* Groups & permissions
* Role-based dashboards

### 🟢 CRUD Operations

* Categories & blog posts management
* Form handling
* Validation and slug generation

### 🟢 Deployment

* Static & media file configuration
* Deployment on PythonAnywhere
* Production setup

---

## 📂 Project Structure

```
django-blog/
│── blog_main/
│── templates/
│── static/
│── media/
│── manage.py
│── requirements.txt
```

---

## 🚀 Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/django-blog.git
cd django-blog
```

### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Migrations

```bash
python manage.py migrate
```

### 5. Create Superuser

```bash
python manage.py createsuperuser
```

### 6. Run Server

```bash
python manage.py runserver
```



## 🔐 Roles in System

| Role    | Permissions            |
| ------- | ---------------------- |
| Admin   | Full control           |
| Manager | Manage users + content |
| Editor  | Manage posts only      |

---

## 📈 Future Improvements

* REST API integration (Django REST Framework)
* Like/Share system
* Rich text editor (CKEditor)
* Email notifications
* Pagination optimization

---

## 🙌 Author

**Amal Aji**

* GitHub: https://github.com/Cyber-Dome
* LinkedIn: https://linkedin.com/in/amal-aji-0a294932b
* Blog: https://www.domebytes.online

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
