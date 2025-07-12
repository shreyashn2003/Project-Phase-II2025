# 🚗 Vehicle Service Management System

![Developer](https://img.shields.io/badge/Developed%20By%20%3A-Sumit%20Kumar-red)

A Django-based web application that automates vehicle servicing operations, allowing customers, mechanics, and admins to interact efficiently. It features dashboards, notifications, and request tracking for seamless vehicle service management.

---

## 📸 Screenshots

### Home Page
![Home](https://github.com/sumitkumar1503/vehicleservicemanagement/blob/master/static/screenshots/home.png?raw=true)

### Admin Dashboard (Dark Theme)
![Admin Dark](https://github.com/sumitkumar1503/vehicleservicemanagement/blob/master/static/screenshots/admin_dark.png?raw=true)

### Admin Dashboard (Light Theme)
![Admin Light](https://github.com/sumitkumar1503/vehicleservicemanagement/blob/master/static/screenshots/admin_light.png?raw=true)

### Mechanic Dashboard
![Mechanic](https://github.com/sumitkumar1503/vehicleservicemanagement/blob/master/static/screenshots/mechanic_dashboard.png?raw=true)

### Customer Dashboard
![Customer](https://github.com/sumitkumar1503/vehicleservicemanagement/blob/master/static/screenshots/customer_dashboard.png?raw=true)

---

## 🔧 Features

### 👤 Customer
- Register and log in securely
- Submit vehicle service requests
- Track request status and mechanic responses
- View service history

### 🧑‍🔧 Mechanic
- View and accept service requests
- Update request progress
- Track assigned tasks and schedules

### 👨‍💼 Admin
- Manage customers and mechanics
- Assign tasks and track service performance
- Generate reports and dashboards
- Theme switching (Dark/Light mode)

---

## 🛠 Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite3
- **Authentication**: Django Auth
- **Others**: Django Templates, Static Files, Git

---

## 🚀 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/sumitkumar1503/vehicleservicemanagement.git
cd vehicleservicemanagement

# Create and activate virtual environment (optional but recommended)
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Run the development server
python manage.py runserver
