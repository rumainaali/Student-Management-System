# Student Management System

This is a student management system built using **Django 6**, **HTML 5**, **CSS 3**, and **Bootstrap 5.3.8** with a **Bootswatch** theme.

<img width="1364" height="680" alt="image" src="https://github.com/user-attachments/assets/c5e74f52-f26d-4564-a48f-6e33994ad57b" />


## Table of Contents 
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Run the application](#run-the-application)
- [Run the tests](#run-the-tests)
- [View the application](#view-the-application)


## Prerequisites

Install the following prerequisites:

1. [Python 3.8-3.11](https://www.python.org/downloads/)
<br> This project uses **Django v6.0.3**. For Django to work, you must install a correct version of Python on your machine.
2. [Visual Studio Code](https://code.visualstudio.com/download)

## Installation

### 1. Create a virtual environment

From the **root** directory, run:

```bash
python -m venv venv
```

### 2. Activate the virtual environment

From the **root** directory, run:

On macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\scripts\activate
```

### 3. Install required dependencies

From the **root** directory, run:

```bash
pip install -r requirements.txt
```

### 4. Run migrations

From the **root** directory, run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

### 5. Create an admin user to access the Django Admin interface

From the **root** directory, run:

```bash
python manage.py createsuperuser
```

When prompted, enter a username, email, and password.

## Run the application

From the **root** directory, run:

```bash
python manage.py runserver
```

## Run the tests

From the **root** directory, run:

```bash
python manage.py test --pattern="tests.py"

```

## View the application

Go to http://127.0.0.1:8000/ to view the application.

## View Student


<img width="1354" height="682" alt="image" src="https://github.com/user-attachments/assets/a5588d79-ff0b-400b-afa5-3f82d8bd9c62" />

Displays the student details, like student number, first name, last name, email, field of study and gpa


## Update Student


<img width="1343" height="680" alt="image" src="https://github.com/user-attachments/assets/fb86ffe3-7321-4b6c-b13d-7dbcc350e7b3" />


<img width="1365" height="672" alt="image" src="https://github.com/user-attachments/assets/a85100f9-c6a0-41aa-bce8-72ad94301ecb" />


<img width="1364" height="679" alt="image" src="https://github.com/user-attachments/assets/0dc283ff-10df-4286-bf02-5a25edc878a2" />


## Add Student


<img width="1326" height="642" alt="image" src="https://github.com/user-attachments/assets/098f36dd-c16f-473a-b067-98fc246a93c4" />


<img width="1346" height="678" alt="image" src="https://github.com/user-attachments/assets/6b055535-affd-4bb9-8e36-a2017a475148" />


<img width="1357" height="629" alt="image" src="https://github.com/user-attachments/assets/4b0764e5-262a-4fb1-9f39-ae360e6276f0" />


## Delete Student


<img width="1365" height="683" alt="image" src="https://github.com/user-attachments/assets/566446c9-7f9a-4609-90ca-c13639069d52" />


<img width="1365" height="669" alt="image" src="https://github.com/user-attachments/assets/5f2eadef-bf0a-46a0-aa77-8f5ab9e74de4" />






