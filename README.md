# Task Manager

This is a simple Django project named `task_manager` with PostgreSQL configured.
It includes a Task model with CRUD operations.

## Features
- Add, view, update, and delete tasks
- Fields: title, description, status, created_at, updated_at

## Setup Instructions
1. Clone the repository
2. Create a virtual environment and install dependencies
3. Configure PostgreSQL in `settings.py`
4. Run migrations and start the server

```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

