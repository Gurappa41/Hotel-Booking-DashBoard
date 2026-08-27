# 🏨 BookMyStay – Hotel Booking Web Application

**BookMyStay** is a full-stack hotel booking web application developed using **Python, Django, MySQL, HTML, CSS, JavaScript, and Bootstrap**.

The application is designed to provide a simple platform where **customers can discover hotels and send booking requests**, while **hotel providers can manage their properties and respond to customer requests**.

The project focuses on implementing a complete real-world workflow, including authentication, hotel management, booking requests, image handling, database operations, and email communication.

---

## 🚀 Key Features

### 👤 Customer Features

* Customer registration and login
* Search hotels based on location
* Browse available hotels
* View complete hotel details
* View hotel images, descriptions, pricing, address, and ratings
* Submit hotel booking requests
* Receive booking responses through email
* View booking information and history

### 🏨 Hotel Provider Features

* Provider registration and login
* Add new hotel properties
* Edit and update hotel information
* Manage pricing, address, descriptions, and other details
* Upload multiple hotel images
* Delete individual hotel images
* View customer booking requests
* Accept booking requests
* Manage booking and acceptance history

### 📩 Booking & Email System

* Customer booking request workflow
* Provider-side request management
* Booking acceptance process
* Automated email notifications
* Email confirmation/response to customers
* Booking status and history management

### 🔎 Hotel Discovery

* Location-based hotel search
* Dynamic hotel listings
* Hotel cards with important information
* Dedicated hotel details pages
* Star-based hotel classification
* Responsive hotel image display

---

## 🛠️ Technology Stack

**Backend**

* Python
* Django
* Django ORM

**Frontend**

* HTML5
* CSS3
* JavaScript
* Bootstrap
* Bootstrap Icons

**Database**

* MySQL

**Other**

* Django Templates
* Email Integration
* Media/Image Handling

---

## 🔄 How It Works

```text
Customer
   ↓
Register / Login
   ↓
Search Hotels
   ↓
View Hotel Details
   ↓
Send Booking Request
   ↓
Hotel Provider Receives Request
   ↓
Provider Accepts Request
   ↓
Customer Receives Email
   ↓
Booking History Updated
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/BookMyStay.git
cd BookMyStay
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure MySQL

Create a MySQL database and update the database credentials in Django's `settings.py`.

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'bookmystay',
        'USER': 'root',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

### 5. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Start the Server

```bash
python manage.py runserver
```

Open the application in your browser:

```text
http://127.0.0.1:8000/
```

---

## 📚 What I Learned

Developing **BookMyStay** gave me practical experience in building a complete web application using Django.

Through this project, I worked with **Django models, views, forms, URL routing, templates, ORM, MySQL, CRUD operations, authentication, sessions, image uploads, and email integration**.

One of the main learning experiences was implementing the interaction between **customers and hotel providers**. The application handles the complete flow from hotel discovery and booking requests to provider approval, email communication, and booking history.

This project also helped me understand how frontend and backend components work together with a database to create a functional and responsive web application.

---

## 🔮 Future Enhancements

Some features that can be added in future versions include:

* 💳 Online payment integration
* 🛏️ Room availability management
* ⭐ Customer reviews and ratings
* 🔍 Advanced hotel filters
* ❌ Booking cancellation
* 🗺️ Map and location integration
* 🔐 OTP and password reset
* 🔗 REST API using Django REST Framework
* ☁️ Cloud deployment

---

## 👨‍💻 Developer

**Gurappa**
B.Tech – Computer Science & Engineering (AI & ML)

**Skills:** Python | Django | MySQL | HTML | CSS | JavaScript | Bootstrap

---

## ⭐ Project Highlights

* Full-stack Django web application
* Customer and hotel provider workflows
* MySQL database integration
* Hotel and image management
* Booking request and approval system
* Automated email communication
* Responsive Bootstrap interface
* Real-world CRUD and database operations

---
