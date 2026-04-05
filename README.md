# finance-dashboard-backend
Finance Data Processing and Access Control Backend
# Finance Data Processing and Access Control Backend

## Project Description
This backend system manages financial records and provides role-based access control for different users such as Viewer, Analyst, and Admin.

## Features
- User and Role Management
- Financial Records CRUD
- Dashboard Summary APIs
- Access Control Logic
- Validation and Error Handling
- Data Persistence with Database

## Technologies Used
- Python
- Flask
- SQLite / MySQL
- Pandas
- REST APIs

## API Endpoints

### User Management
POST /users
GET /users

### Financial Records
POST /records
GET /records
PUT /records/<id>
DELETE /records/<id>

### Dashboard
GET /summary
GET /analytics

## Setup Instructions

1. Clone repository
git clone https://github.com/rakhijrajput/finance-dashboard-backend.git

2. Install dependencies
pip install -r requirements.txt

3. Run application
python app.py
