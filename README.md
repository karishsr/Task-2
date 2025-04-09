Overview
This repository contains a simple Jenkins pipeline setup for CI/CD automation.

Objective
The goal of this task is to:

Set up a basic Jenkins pipeline.

Automate the build and deployment of an application using Jenkins.

Tools Used
Jenkins
GitHub

Steps Followed
Installed Jenkins.

Created a Jenkinsfile in the repository with build and deployment steps.

Configured Jenkins to trigger the pipeline upon code commits.

Added pipeline stages:

Build: Compile and prepare the application.

Test: Run automated tests.

Deploy: Deploy the application to a test or production environment.

Tested the pipeline by pushing changes and observing Jenkins execution.

Files Included
Jenkinsfile – Defines the CI/CD pipeline.
src/ – Application source code.
README.md – This documentation.

How to Run
Clone the repository:
git clone https://github.com/karishsr/Task-2.git

Set up Jenkins and create a pipeline with this repository.

Configure webhooks to trigger builds on code push.

Monitor the pipeline execution in the Jenkins dashboard.

Outcome
This project demonstrates how to automate software deployment using Jenkins in a DevOps pipeline.

