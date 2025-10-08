# Employee Management API

A simple CRUD API built with FastAPI and SQLAlchemy for managing employee records.

## Features
- Create, Read, Update, Delete employees
- Email validation
- SQLite database
- RESTful API design

## Setup

**1. Clone the repository**
git clone https://github.com/Ujja12287/employee-crud-api.git
cd employee-crud-api

**2. Create virtual environment**
python -m venv venv
venv\Scripts\activate

**3. Install dependencies**
pip install fastapi uvicorn sqlalchemy pydantic email-validator

**4. Run the server**
uvicorn main:app --reload

**5. Open API documentation**

Visit http://127.0.0.1:8000/docs

## API Endpoints

- POST /employees - Create new employee
- GET /employees - Get all employees
- GET /employees/{emp_id} - Get employee by ID
- PUT /employees/{emp_id} - Update employee
- DELETE /employees/{emp_id} - Delete employee

## Tech Stack
- FastAPI
- SQLAlchemy
- SQLite
- Pydantic
