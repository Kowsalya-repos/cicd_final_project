# CI/CD Pipeline Final Project

## Project Overview
This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions, Tekton Pipelines, and OpenShift. The pipeline automates the process of linting, testing, building, and deploying an application.

## Technologies Used
- GitHub
- GitHub Actions
- Tekton Pipelines
- OpenShift
- Python
- flake8 (Code Linting)
- nose (Unit Testing)


## CI/CD Pipeline Workflow

The CI/CD pipeline performs the following steps:

1. **Code Checkout**
   - The source code is retrieved from the GitHub repository.

2. **Install Dependencies**
   - Python dependencies are installed using pip.

3. **Code Linting**
   - The code is checked for style and syntax errors using flake8.

4. **Run Unit Tests**
   - Unit tests are executed using the nose testing framework.

5. **Pipeline Execution**
   - Tekton tasks manage the build and test pipeline within OpenShift.

6. **Deployment**
   - The application is deployed automatically using OpenShift pipelines.
