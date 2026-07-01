CodeAlpha CI/CD Pipeline using Azure
Project Overview
This project demonstrates the implementation of a Continuous Integration and Continuous Deployment (CI/CD) pipeline using GitHub Actions and Microsoft Azure App Service.
The pipeline automatically builds, validates, and deploys the application whenever changes are pushed to the GitHub repository.

Features
* Automated CI/CD workflow
* GitHub Actions integration
* Azure App Service deployment
* Docker-based application deployment
* Continuous integration and continuous deployment
* Version-controlled workflow automation
  
Technologies Used
* Python
* Docker
* GitHub Actions
* Microsoft Azure App Service
* YAML Workflows
* Git & GitHub

Project Structure
CodeAlpha_CICD_Pipeline/
│
├── app.py
├── Dockerfile
├── requirements.txt
│
└── .github/
    └── workflows/
        ├── ci-cd.yml
        └── main_geethanjali-codealpha-cicd.yml

CI/CD Workflow
1. Code is pushed to GitHub.
2. GitHub Actions workflow is triggered automatically.
3. Dependencies are installed.
4. Application validation is performed.
5. Docker image is built.
6. Azure App Service deployment workflow is executed.
7. Application is deployed automatically.

Azure Services Used
* Azure App Service
* Azure Deployment Center
* Azure for Students Subscription

Outcome
Successfully implemented an automated CI/CD pipeline that integrates GitHub Actions with Microsoft Azure App Service, enabling streamlined application deployment and DevOps workflow automation.

Author
Geethanjali V N
