<div align="center">

<img width="1885" height="917" alt="Screenshot 2026-05-22 161713" src="https://github.com/user-attachments/assets/13549c22-79bc-4bc3-9a90-a246d54c9031" />


# 🌊 Market Wave Retail CRM
### AI-Powered Retail Management System

<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white">
<img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white">
<img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white">
<img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge">

---

### Where AI Meets Smart Shopping. Ride the future of commerce.

A modern Django-based Retail CRM platform designed to streamline customer management, product handling, order processing, and analytics through a clean and scalable interface..

</div>

---

# 📖 Overview

**Market Wave Retail CRM** is a comprehensive Customer Relationship Management system built using Django. It helps businesses efficiently manage customers, products, orders, tags, and sales analytics from a centralized dashboard.

The project follows Django’s MVT architecture and emphasizes clean UI design, maintainable code structure, and scalable business operations.

---

# ✨ Features

## 🔐 Authentication System

- User Registration
- User Login
- Secure Authentication
- Logout Functionality

---

## 📊 Dashboard & Analytics

- Interactive Admin Dashboard
- Sales Analytics Visualization
- Chart.js Integration
- Business Performance Insights

---

## 👥 Customer Management

- Add Customers
- Update Customer Information
- Delete Customers
- View Customer Details
- Track Customer Orders

---

## 🛍️ Product Management

- Add Products
- Update Products
- Delete Products
- Product Images
- Product Categories
- Indoor & Outdoor Product Types
- Product Filtering System

---

## 📦 Order Management

- Create Orders
- Update Order Status
- Delete Orders
- Order Tracking

Order Status:

- Pending
- Out for Delivery
- Delivered

---

## 🏷️ Tag Management

- Create Product Tags
- Update Tags
- Delete Tags
- CSV Tag Import System

---

## 📈 Data Analytics

- Sales Charts
- Customer Analytics
- Product Insights
- Visual Business Reports

---

# 🏗️ Project Structure

```bash
Market_Wave_Retail_CRM/
│
├── account/
│   ├── migrations/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── filters.py
│
├── db/
│   ├── settings.py
│   └── urls.py
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── template/
│   ├── account/
│   ├── main.html
│   ├── navbar.html
│   └── status.html
│
├── media/
├── screenshots/
├── manage.py
└── project.txt
```

---

# 🛠️ Tech Stack

| Technology | Usage |
|------------|--------|
| Python | Backend |
| Django | Web Framework |
| SQLite | Database |
| HTML5 | Structure |
| CSS3 | Styling |
| Bootstrap 5 | Responsive UI |
| JavaScript | Dynamic Features |
| Chart.js | Data Visualization |

---

# 🚀 Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Soubhagya-Kabiraj/Market_Wave_Retail_CRM.git
```

---

## 2️⃣ Move into Project Directory

```bash
cd Market_Wave_Retail_CRM
```

---

## 3️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
```

Activate Environment:

```bash
venv\Scripts\activate
```

### Linux / Mac

```bash
source venv/bin/activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install django django-filter
```

---

## 5️⃣ Apply Migrations

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```

---

## 6️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

---

## 7️⃣ Run Development Server

```bash
python manage.py runserver
```

Open in browser:

```bash
http://127.0.0.1:8000/
```

---

# 📷 Website Screenshots

<div align="center">

| Landing Page | Product List |
|--------------|---------------|
| <img width="1885" height="917" alt="Screenshot 2026-05-22 161713" src="https://github.com/user-attachments/assets/c212a4da-5d6c-44f7-b175-23764c049dd9" /> | <img width="1883" height="915" alt="Screenshot 2026-05-22 161800" src="https://github.com/user-attachments/assets/08b03c04-69bd-4756-a493-a30effdcb3fa" /> |

| Customer List | Customer Detail |
|----------------|-----------------|
| <img width="1887" height="911" alt="Screenshot 2026-05-22 161841" src="https://github.com/user-attachments/assets/169efe46-b581-4fed-a579-6a9ba52784c4" /> | <img width="1888" height="914" alt="Screenshot 2026-05-22 161943" src="https://github.com/user-attachments/assets/c402e5fd-9d0e-4d1d-a38b-635a2aeb9c39" /> |

| Order List | Tag List |
|-------------|-----------|
| <img width="1880" height="914" alt="Screenshot 2026-05-22 162009" src="https://github.com/user-attachments/assets/66b2c28c-7533-4bd8-9154-ed70cb17e887" /> | <img width="1879" height="914" alt="Screenshot 2026-05-22 162112" src="https://github.com/user-attachments/assets/33c5ae83-baff-4d1b-88d1-3b5a25d1995e" /> |

| Import CSV File | Analytics Page |
|------------------|----------------|
| <img width="1888" height="916" alt="Screenshot 2026-05-22 162359" src="https://github.com/user-attachments/assets/c502f4cc-105d-4e00-b890-efa573a9b6d8" /> | <img width="1884" height="918" alt="Screenshot 2026-05-22 162046" src="https://github.com/user-attachments/assets/f2f2dc7b-fc1e-465c-bee5-db0173b64da5" /> |

</div>

---

# 📄 Website Pages

✅ Landing Page  
✅ Dashboard Page  
✅ Product List Page  
✅ Customer List Page  
✅ Customer Detail Page  
✅ Order List Page  
✅ Tag Management Page  
✅ CSV Import Page  
✅ Analytics Dashboard  
✅ Login Page  
✅ Register Page  

---

# 🔐 Future Improvements

- AI-Based Product Recommendations
- Email Notifications
- Advanced Sales Prediction
- Export Reports to PDF & Excel
- Multi-Admin Support
- Cloud Database Integration

---

# 🤝 Contribution

Contributions are welcome.

### Steps to Contribute

#### 1️⃣ Fork the Repository

#### 2️⃣ Create a Feature Branch

```bash
git checkout -b feature-name
```

#### 3️⃣ Commit Your Changes

```bash
git commit -m "Added new feature"
```

#### 4️⃣ Push Changes

```bash
git push origin feature-name
```

#### 5️⃣ Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

### Soubhagya Kabiraj

**Market Wave — Where AI Meets Smart Shopping.**

---

<div align="center">

### ⭐ If you like this project, give it a star ⭐

Made with ❤️ using Django

</div>
