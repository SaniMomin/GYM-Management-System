# Gym Management System

Gym Management System is a Django-based web application designed for streamlined gym administration. This project empowers a single admin to manage members and trainers effectively through a centralized dashboard. It uses custom authentication—admin credentials (email and password) are stored in the database, not using Django's default auth system.

---

## 🔗 Links

- 📁 **GitHub Repository**: [https://github.com/SaniMomin/GYM-Management-System](https://github.com/SaniMomin/GYM-Management-System)

---

## 🚀 Key Highlights

### 🔐 Admin Login Only:
- Secure access using custom email/password credentials fetched directly from a database table.
  
### 👤 Member Management:
- Add new members
- View list of members
- Search members by name or ID
- Update and delete member details
  
### 🏋️ Trainer Management:
- Add new trainers
- View list of trainers
- Search trainers
- Update and delete trainer information

---

## 🛠️ Tech Stack

### Framework:
- Python Django (MVT Architecture)
### Frontend:
- HTML, CSS
### Database:
- SQLite3 (can be switched to PostgreSQL, MySQL, etc.)

---

## Folder Structure

config/
├── calc
│ ├── _pycache/
│ ├── migrations/
│ ├── __init__.py
│ ├── admin.py
│ ├── app.py
│ ├── models.py
│ ├── tests.
│ ├── urls.py
│ └── views.py
├── config
│ ├── _pycache/
│ ├── __init__.py
│ ├── asgi.py
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── static
│ ├── css/
│   ├── About.css
│   ├── Contact.css
│   └── ...
├── Template
│   ├── About.html
│   ├── Contact.html
│   └── ...
├── db.sqlite3
├── manage.py

---

## ⚙️ Installation & Setup
1. **Clone the Repository**
   git clone https://github.com/your-username/gym-management-system.git
   cd gym-management-system
2. **Create a Virtual Environment & Activate**
   python -m venv env
   source env/bin/activate  ***Windows: env\Scripts\activate***
3. **Install Required Packages**
   pip install -r requirements.txt
4. **Run Migrations**
   python manage.py makemigrations
   python manage.py migrate
5. **Create Admin Record (via shell)**
   python manage.py shell
   from your_app.models import Admin
   Admin.objects.create(email="admin@example.com", password="your_password")
   exit()
6. **Start the Development Server**
   python manage.py runserver
   ***Visit: http://127.0.0.1:8000/***

---

## 👤 Author 
- **Sani Momin**
- 📧 wdev.sani@gmail.com
- 💼 [GitHub Profile](https://github.com/GYM-Management-System)

---

## 📜 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 🙌 Acknowledgements
- [Python](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [SQLite](https://www.sqlite.org/index.html)
- [GitHub](https://github.com/)
