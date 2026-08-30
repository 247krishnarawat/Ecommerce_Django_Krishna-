# CheckInn — Full-Stack Django E-Commerce Platform

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Django-5.1-092E20?style=flat-square&logo=django&logoColor=white" alt="Django 5" />
  <img src="https://img.shields.io/badge/Database-SQLite%20/%20PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Frontend-HTML5%20/%20CSS3%20/%20JS-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/Architecture-MVT%20Pattern-4B32C3?style=flat-square" alt="Django MVT" />
</p>

---

## 📖 Overview

**CheckInn** is a full-featured, full-stack e-commerce web application built using the **Django** web framework. The application provides an end-to-end online shopping experience featuring dynamic product catalogs, apparel categories (tops, bottoms, footwear, accessories), shopping cart management, user authentication, and checkout processing.

---

## ✨ Features & Functional Modules

### 1. 🛍️ Dynamic Product Catalog & Storefront
- **Categorized Inventory**: Seamless browsing across apparel categories including upperwear, trousers/pants, shoes, and lifestyle accessories.
- **Product Details**: High-resolution image showcases, pricing, item descriptions, and stock availability.
- **Search & Filtering**: Filter items by category, price ranges, and keyword tags.

### 2. 🛒 Shopping Cart & Order Processing
- **Session-Based Cart**: Add, update quantities, or remove items in real time with dynamic subtotal calculations.
- **Checkout Workflow**: Streamlined customer shipping address input and order summary confirmation.

### 3. 🔐 User Authentication & Account Management
- **Registration & Login**: Secure user onboarding leveraging Django's built-in authentication framework and password hashing.
- **User Dashboard**: Order history tracking and profile management.

### 4. 🛠️ Administrative Control Center
- **Django Admin Interface**: Full CRUD management of product inventory, categories, order statuses, and user accounts.
- **Media Asset Handling**: Automated upload and static file management for product images.

---

## 🏗️ Architecture & Tech Stack

```text
CheckInn E-Commerce
├── Backend & Framework: Python & Django 5.x (Model-View-Template pattern)
├── Database: SQLite (Development) / PostgreSQL compatible
├── Frontend: HTML5, CSS3, JavaScript, Django Template Language (DTL)
└── Static Assets: Product imagery, CSS styles, and responsive UI components
```

---

## 📁 Repository Structure

```text
Ecommerce_Django_Krishna-/
├── Django_project_2/
│   └── CheckInn02/
│       └── CheckInn/
│           ├── CheckInn/          # Core Django project configuration & settings
│           │   ├── settings.py
│           │   ├── urls.py
│           │   └── wsgi.py
│           ├── static/            # Static assets (images, CSS, JS)
│           │   ├── css/
│           │   ├── js/
│           │   └── images/        # Product catalog imagery
│           ├── templates/         # HTML Jinja/Django templates
│           ├── manage.py          # Django CLI management utility
│           └── db.sqlite3         # SQLite database
├── requirements.txt               # Python package dependencies
└── README.md                      # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9 or higher
- pip package manager

---

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/247krishnarawat/Ecommerce_Django_Krishna-.git
   cd Ecommerce_Django_Krishna-
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   # Windows:
   venv\Scripts\activate
   # macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Navigate to the Django project directory and apply migrations:**
   ```bash
   cd Django_project_2/CheckInn02/CheckInn
   python manage.py migrate
   ```

5. **Create a superuser for admin access (Optional):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Start the development server:**
   ```bash
   python manage.py runserver
   ```
   Open **`http://127.0.0.1:8000/`** in your browser. Access the Django Admin panel at `http://127.0.0.1:8000/admin/`.

---

## 🔮 Future Enhancements

- 💳 Integration with payment gateways (Stripe, Razorpay, or PayPal)
- 📦 Real-time order tracking with email invoice notifications
- ⭐ User product reviews, star ratings, and wishlist features
