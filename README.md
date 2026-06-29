# ✈️ Travel Agency Management System

A web-based **Travel Agency Management System** developed using **Django**. This application allows travel agencies to efficiently manage clients, destinations, travel packages, reservations, and payments through a modern and user-friendly interface.

The project follows the **MVC/MVT architecture** provided by Django and uses Django's built-in features such as ORM, authentication, templates, forms, and URL routing.

---

## 📌 Features

### 👤 Authentication & Authorization

- User Login
- User Logout
- Django Authentication System
- User Roles and Permissions
- Protected Dashboard

### 👥 Client Management

- Create Client
- View Client Details
- Update Client Information
- Delete Client
- Search Clients

### 🌍 Destination Management

- Add Destinations
- Edit Destinations
- Delete Destinations
- Destination Details

### 🏨 Travel Package Management

- Create Travel Packages
- Assign Destinations
- Set Departure and Return Dates
- Manage Available Seats
- Package Pricing

### 📅 Reservation Management

- Book a Travel Package
- Update Reservation
- Cancel Reservation
- Reservation History

### 💳 Payment Management

- Record Payments
- Payment Status
- Payment History

### 📊 Dashboard

- Total Clients
- Total Reservations
- Available Packages
- Revenue Statistics

---

# 🛠 Technologies Used

- Python 3
- Django (Latest Version)
- Django ORM
- Django Templates
- Django Forms (ModelForm)
- Bootstrap 5
- HTML5
- CSS3
- JavaScript
- SQLite (Development Database)

---

# 📂 Database

The application uses **Django ORM** for all database interactions.

Main entities:

- User
- Client
- Destination
- Travel Package
- Reservation
- Payment

Relationships are implemented using:

- ForeignKey
- OneToOneField (where applicable)
- Many-to-Many relationships (if needed)

---

# 📝 Forms

The application uses Django Forms and ModelForms for:

- Client Registration
- Package Creation
- Reservation
- Payment
- Authentication

All forms include server-side validation.

---

# 🔒 Authentication

The project uses Django's built-in authentication system.

Features include:

- Login
- Logout
- Password Hashing
- Session Management
- Authorization using Django Permissions
- Protected Views

---

# 🗃 CRUD Operations

Complete CRUD operations are implemented for:

- Clients
- Destinations
- Travel Packages
- Reservations
- Payments

---

# 🎨 User Interface

The interface is built using:

- Bootstrap 5
- Responsive Layout
- Navigation Bar
- Sidebar
- Cards
- Tables
- Forms
- Alerts

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/travel-agency-management.git
```

Move into the project

```bash
cd travel-agency-management
```

Create a virtual environment

```bash
python -m venv venv
```

Activate it

Windows

```bash
venv\Scripts\activate
```

Linux/macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run migrations

```bash
python manage.py migrate
```

Create an administrator account

```bash
python manage.py createsuperuser
```

Start the development server

```bash
python manage.py runserver
```

Open your browser

```
http://127.0.0.1:8000/
```

Admin Panel

```
http://127.0.0.1:8000/admin/
```

---

# 📚 Django Components Used

- Django ORM
- Django Templates
- Django Forms
- Django Authentication
- Django Admin
- Static Files
- Media Files
- URL Routing
- Generic Views
- Function-Based Views

# 👨‍💻 Author

Developed by aaddi yacine as a university project for learning Django web development and demonstrating the implementation of a complete Travel Agency Management System using Django best practices.
