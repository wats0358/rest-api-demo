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
   python app.py
5. The API will be running at http://127.0.0.1:8000
6. Use **test-api.http** to test the REST API using the REST Client extension in Visual Studio Code.

## Deploying to Azure

### What is Azure App Service?

[Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/) is a fully managed platform for building, deploying, and scaling web apps. With Azure App Service, you can host web applications, REST APIs, and mobile backends in any programming language without managing infrastructure. It provides integrated continuous deployment and scaling features, making it a powerful and flexible solution for cloud-based web hosting.

Some key features of Azure App Service include:
- **Automatic Scaling**: Scale up or out depending on traffic.
- **Continuous Integration/Continuous Deployment (CI/CD)**: Easily integrate with GitHub, Bitbucket, or Azure DevOps for automated deployments.
- **Custom Domains and SSL**: Secure your apps with custom domains and certificates.
- **Load Balancing**: Built-in load balancing to handle high-traffic applications.
- **Monitoring and Diagnostics**: Access real-time monitoring and logs for troubleshooting.


You can learn more about Azure App Service and its features in the [official documentation](https://learn.microsoft.com/en-us/azure/app-service/).

To learn how to deploy a Python web app (Django, Flask, or FastAPI) to Azure App Service, refer to the [Quickstart Guide](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-cli%2Cazure-cli-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli). This guide walks you through deploying a Python web app to Azure, leveraging App Service to run your app in a Linux server environment.

