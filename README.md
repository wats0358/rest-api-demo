# Students REST API app w/ Flask

This project shows a REST API application used to manage students data deployed with Flask, that can also be deployed to a Azure App.

## Features

- GET /students: Retrieve a list of all students.
- GET /students/{id}: Retrieve details of a student by ID.
- POST /students: Add a new student.
- PUT /students/{id}: Update an existing student by ID.
- DELETE /students/{id}: Delete a student by ID.

## Prerequisites

Before you can run or deploy this app, you need to have the following installed:

- Python 3.x
- pip (Python package manager)
- Flask (`pip install Flask`)
- gunicorn (`pip install gunicorn`)

## Project Structure

- app.py: Main Flask application 
- requirements.txt: Python dependencies 
- test-api.http: Testing REST API endpoints inside VS code
- README.md: Documentation

## Running Locally

To run the Flask API on your local machine:

1. Clone this repository:

   ```bash
   git clone https://github.com/wats0358/
   
2. Navigate to the project directory:
   ```bash
   cd flask-rest-api-demo
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the application:
   ```bash
   python3 app.py
5. The API will be running at http://127.0.0.1:8000
6. Use **test-api.http** to test the REST API using the REST Client extension in Visual Studio Code.

## Deploying to Azure



