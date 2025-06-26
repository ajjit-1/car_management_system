# Car Management System 🚗 (Django Project)

This is a web-based Car Management System built using Django. It allows users to manage car records, including details like car model, owner, registration number, and maintenance history.

## 🚀 Features

- Add, view, update, and delete car records
- Owner details management
- Maintenance history tracking
- Admin panel for data management
- Responsive frontend using Django templates

## 🔧 Tech Stack

- Python 3.x
- Django 4.x
- SQLite (default)
- HTML, CSS, JavaScript (for frontend)

##  Project Structure
online_car_project/
├── car/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── templates/all html
├── online_car_project/
│ ├── settings.py
│ ├── urls.py
├── db.sqlite3
└── manage.py
## ⚙️ Setup Instructions

1. Clone the repository:  cd car-management-system

2. Create a virtual environment and activate it:python -m venv venv
                                                venv\Scripts\activate

3. Install dependencies: pip install -r requirements.txt

4. Run migrations: python manage.py makemigrations
                   python manage.py migrate


5. Create a superuser:python manage.py createsuoeruser

6.run this project : - python manage.py runserver
