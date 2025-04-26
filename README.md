# StudentCourseAPI
A Flask-based REST API for managing student records and validating course IDs (CSE/DSE).

## Endpoints
- `POST /create`: Create a student with name, personnummer, and courses_passed.
- `PUT /update/<id>`: Update student details.

## Setup
```bash
pip install flask
python api.py
