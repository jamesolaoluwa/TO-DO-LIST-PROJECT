# Flask To-Do Application

## Description

Welcome to my simple yet effective To-Do application built with Flask, designed to help manage daily tasks efficiently. It features task addition, deletion, updating, and viewing functionalities, along with priority setting and due date options for each task.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Setup

1. Clone the repository:
   ```bash
   git clone [repository-url]

**1.Navigate to the project directory:**

cd flask-todo-app

**2. install the required packages:**

pip install -r requirements.txt

**3. Initialize the database:**

from app import db
db.create_all()

**4. Run the application:**

python app.py

### Key Features
Add Tasks: Users can add new tasks to their to-do list. Each task includes a description, a priority level, and an optional due date.

Update Tasks: Tasks can be updated at any time. This includes changing the description, the priority, and the completion status.

Delete Tasks: Any task can be removed from the list.

View Tasks: All tasks are displayed on the main page, with details such as creation date, due date, and priority.

Task Completion Toggle: Each task has a completion status that can be toggled to mark the task as completed or incomplete.

**Technologies Used**

Python: The primary programming language used.

Flask: ightweight WSGI web application framework.

SQLAlchemy: SQL toolkit and ORM for Python.

SQLite: Database engine used for storing tasks.
