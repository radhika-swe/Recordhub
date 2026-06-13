# 📦 RecordHub

RecordHub is a Django-based CRUD (Create, Read, Update, Delete) web application built using Django ORM. It allows efficient management of records with a simple and clean user interface.

---

## 🚀 Features

* Create new records
* View all records
* Update existing records
* Delete records
* Django ORM-based database handling
* Admin panel support
* Template-based frontend

---

## 🛠️ Tech Stack

* Python
* Django
* SQLite (default database)
* HTML, CSS (Templates)
* Django ORM

---

## 📁 Project Structure

```
RecordHub/
│
├── manage.py
├── requirements.txt
├── db.sqlite3 (not pushed to GitHub)
│
├── templates/
├── static/
├── media/
│
├── your_app/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│
└── project/
    ├── settings.py
    ├── urls.py
    ├── wsgi.py
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/RecordHub.git
cd RecordHub
```

### 2. Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run migrations

```bash
python manage.py migrate
```

### 5. Create superuser (admin)

```bash
python manage.py createsuperuser
```

### 6. Run development server

```bash
python manage.py runserver
```

---

## 🌐 Open in browser

```
http://127.0.0.1:8000/
```

Admin panel:

```
http://127.0.0.1:8000/admin
```

---

##DEMO RUN:
    *username=admin
    *password=admin123

---

## 📌 Notes

* Do NOT commit `venv/` or `db.sqlite3`
* Always install dependencies using `requirements.txt`
* This project uses Django ORM for database operations

---

## 👩‍💻 Author

Radhika
Django Developer (Learning Project)

---

## 📜 License

This project is for educational purposes.
