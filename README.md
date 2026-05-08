# 🚀 Django SaaS Backend

A scalable backend application built using Django and Django REST Framework, designed to support SaaS-style user management and REST APIs.
## Features

- User Authentication
- REST APIs
- Database Integration
- Django Admin Panel
- Modular App Structure

## Tech Stack

- Python
- Django
- Django REST Framework
- SQLite
- Git & GitHub

## Installation

```bash
git clone https://github.com/KritiSandal/django-saas-backend.git
cd django-saas-backend
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## API Endpoints

| Method | Endpoint | Description |
|  ---  | --- | --- |
| POST | /login | User Login |
| POST | /register | User Registration |
| GET | /profile | User Profile |

## Project Structure

```bash
django-saas-backend/
│
├── users/
├── api/
├── core/
├── manage.py
```

## Future Improvements

- JWT Authentication
- Multi-tenancy
- Role-based Access
- Docker Deployment

## Author

Kriti Sandal
