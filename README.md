# Django Todo API

## Overview

This repository contains a Django-based RESTful API for managing todo tasks. The API is built using the Django Rest Framework and provides endpoints for creating, updating, retrieving, and deleting todo tasks. It includes features such as serialization and customizable task filtering.

## Features

- Create, read, update, and delete todo tasks.
- Serialization of task data in JSON format.
- Customizable task filtering based on various parameters.

## Requirements

- Python 3.x
- Django 4.0
- Django Rest Framework 3.14.0
- asgiref 3.7.2
- pytz 2023.3
- sqlparse 0.4.4
- typing_extensions 4.7.1
- tzdata 2023.3
- Other dependencies (mention any additional dependencies your project might have)

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Django-Todo-API.git

2. Navigate to the Project Directory:
   cd TodoAPI

3. Activate the Virtual Environment:
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate  # On Windows

4. Install Dependencies:
   pip install -r requirements.txt

5. Apply Migrations:
   python manage.py makemigrations
   python manage.py migrate

6. Run the Development Server:
   python manage.py runserver
   The API will be accessible at http://localhost:8000/api/tasks/
   
## API Endpoint

    GET /api/tasks/: Get a list of all tasks.
    POST /api/tasks/: Create a new task.
    GET /api/tasks/{task_id}/: Retrieve details of a specific task.
    PUT /api/tasks/{task_id}/: Update a specific task.
    DELETE /api/tasks/{task_id}/: Delete a specific task.


 

