# todo-list-django

A simple and efficient API for basic CRUD operations on a to-do list, built with Django REST Framework. It includes a responsive frontend using Bootstrap and CSS, with API calls made via vanilla JavaScript. This project was developed following Dennis Ivy's [tutorial](https://www.youtube.com/playlist?list=PL-51WBLyFTg3k9JKxT7ExP8Xvt4GeG5zc)

## Features
- Task Management: Easily create, view, update, and delete tasks.
- Responsive Design: User-friendly interface that adapts to various devices and screen sizes.
- Django REST Framework: Robust backend for managing API endpoints.
- Bootstrap Integration: Clean and modern UI components.
- Vanilla JavaScript: Simple and efficient API calls without the need for heavy frameworks.
- SQLite Database: Lightweight and easy-to-use database for local development.

## API Endpoints

##### 1. API Overview

- Endpoint: GET /api/
- Description: Displays an overview of the API's urls.

##### 2. Create task

- Endpoint: POST /api/task-create/
- Description: Creates a new task.

##### 3. Retrieve tasks

- Endpoint: GET /api/task-list/
- Description: Retrieves a list of all tasks.

##### 4. Retrieve task

- Endpoint: GET /api/task-detail/{id}/
- Description: Retrieves a specific task.

##### 5. Update task

- Endpoint: PUT /api/task-update/{id}/
- Description: Updates an existing task.

##### 6. Delete task

- Endpoint: DELETE /api/task-delete/{id}/
- Description: deletes a task.

## How to Use

### 1. Clone the repository:
```bash
git clone https://github.com/omarse7a/todo-list-django.git
cd todo-list-django
```

### 2. Set up a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  # On macOS/Linux
.\venv\Scripts\activate   # On Windows
```

### 3. Install the dependencies:
```bash
pip install -r requirements.txt
```

### 4. Apply migrations:
```bash
python manage.py migrate
```
### Run the development server:
```bash
python manage.py runserver
```
