# userLogin
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)

A small project following [this guide](https://learndjango.com/tutorials/django-login-and-logout-tutorial) to help me learn django.
The app allows you to create an account and sign in with said account. 

## Setup (MacOS)

Navigate to the base directory.

Create a new virtual environment called .venv and activate it:

```bash
  $ python3 -m venv .venv
  $ source .venv/bin/activate
```

Install requirements within the virtual environment:

```bash
  (.venv) $ python3 -m pip install -r requirements.txt
```

**Open the file petshop/secretsTemplate.py and follow the instructions inside**

Create a new Sqlite database and run the local server:

```bash
  (.venv) $ python3 manage.py migrate
  (.venv) $ python3 manage.py runserver
```

Navivate to the main page in your web browser at [http://localhost:8000/](http://localhost:8000/)

(Optional) Create an admin user:

```bash
  (.venv) $ python3 manage.py createsuperuser
```

Follow the prompt in the terminal and then navigate to the admin page at [http://localhost:8000/admin/](http://localhost:8000/admin/)
