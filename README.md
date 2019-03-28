# WordCount-Project
A simple word counting website.

# **Django commands**

## Installing Django
```pip3 install django==2.1.7```

## Setting up virtual environment
Creating Virtual Environment

```python3 -m venv myvenv```

Starting virtual environment

```source myvenv/bin/activate```

## Django commands
Creating a new project

```django-admin startproject projectname```

Add an app to a project

```python3 manage.py startapp appname```

Starting the server

```python3 manage.py runserver```

Creating migrations

```python3 manage.py makemigrations```

Migrate the database

```python3 manage.py migrate```

Creating a Super User for the admin panel

```python3 manage.py createsuperuser```

Collecting static files into one folder

```python3 manage.py collectstatic```
