# Django REST API

A simple Django project built to learn Django and how to develop REST APIs using Django Rest Framework (DRF). The application offers basic functionality for interacting with user data.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [API Endpoints](#api-endpoints)

---

## Overview

This project is a simple Django-based REST API that demonstrates how to use **Django**, **Django Rest Framework**, and **serializers** to build a basic API. 

### Key Features:
- **GET /users/**: Retrieve all user data from the database.
- **POST /users/**: Insert new user data into the database.

---

## Installation

To get this application running locally, follow the steps below:

### 1. Clone the repository:

```bash
git clone https://github.com/pavansai0910/Django_rest_api.git
```
### 2. Navigate to the project directory:

```bash
cd django_rest_api
```

### 3. Install requires dependecies:

```bash
pip install django djangorestframework
```
### 4.run the database migrations, and run the application
```bash
python manage.py migrate
```
```bash
python manage.py runserver"
```

## API endpoints
  ### 1. get user data
      localhost:portnumber/api/user

  ### 2. Create users
      localhost:portnumber/api/user/create
