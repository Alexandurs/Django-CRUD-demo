# Django Autos CRUD 🚗

[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/downloads/release/python-3137/)
[![Django 5.2](https://img.shields.io/badge/django-5.2-green.svg)](https://docs.djangoproject.com/en/5.2/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Fully working* CRUD (Create, Read, Update, and Delete) application to manage automobiles and their makes (i.e. Ford, Hyundai, Toyota, Tata, Audi, etc.).

This project is built with **Django 5.2** as a demo app to showcase Django fundamentals:  
- Models & migrations  
- Admin integration  
- Views & templates  
- URL routing  
- Forms & validation  

---

## 🔧 Local Setup

### Clone the repo
```
git clone https://github.com/Alexandurs/django_autos_CRUD.git
cd django_autos_CRUD
```

### Create & activate a virtual environment
```
python -m venv venv
source venv/bin/activate   
```
### Install dependencies
```
pip install -r requirements.txt
```

### Set up the database models
```
python manage.py makemigrations
python manage.py migrate
```

## Start the dev server
```
cd django_autos_CRUD
python manage.py runserver
```

## Create a superuser to login
```
python manage.py createsuperuser

```

---

## 🚀 Features
- Create, view, update, and delete automobile makes and models  
- Django admin enabled for quick data management  
- SQLite database

### Project structure note
If you see **two directories named `django_autos_CRUD/`**, that’s normal in Django:

- The **outer `django_autos_CRUD/`** is the **project root** — it contains `manage.py` and Django apps (e.g., `autos/`).
- The **inner `django_autos_CRUD/`** is the **project package** — it contains `settings.py`, `urls.py`, `asgi.py`, and `wsgi.py` (imported as `django_autos_CRUD.settings`).

This duplication is created by `django-admin startproject` and is standard Django practice.

