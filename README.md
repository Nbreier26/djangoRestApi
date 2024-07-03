# Employee Management API

API RESTful for employee management using Django and Django REST framework.

## Requirements

- Python 3.x
- Django 3.x
- Django REST framework 3.x

## Usage

To run the Employee Management API:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   cd repository-name

2. Make sure Python 3.x is installed. You can check by running:
    ```bash
   python --version

3. Install Django and Django REST framework (if not already installed):
    ```bash
    pip install django djangorestframework

4. Apply database migrations:
    ```bash
    python manage.py migrate

5. Start the development server:
     ```bash
    python manage.py runserver

##API Endpoints
You can access the following endpoints:

GET /api/employees/
List all employees.

POST /api/employees/
Create a new employee.

GET /api/employees/{id}/
Retrieve details of a specific employee.

PUT /api/employees/{id}/
Update details of a specific employee.

DELETE /api/employees/{id}/
Delete a specific employee.
  
