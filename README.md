# ci-cd-final-project

[![CI Workflow](https://github.com/suhanib-18/ci-cd-final-project/actions/workflows/workflow.yml/badge.svg)](https://github.com/suhanib-18/ci-cd-final-project/actions)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)

## Project Name

**ci-cd-final-project**

This repository is named **ci-cd-final-project** and contains the IBM Continuous Integration and Continuous Delivery (CI/CD) Final Project.

### Project name details
- **Project name:** `ci-cd-final-project`
- **Repository name:** `ci-cd-final-project`
- **Author:** suhanib-18
- **Application / Deployment:** `cicd-app`
- **Microservice:** Customer Accounts Service
- **Technologies:** Python 3.9, Flask, Flake8, Nose, Tekton Pipelines, Red Hat OpenShift

### CI/CD overview
- GitHub Actions: `.github/workflows/workflow.yml`
  - Lint with flake8
  - Run unit tests with nose
- Tekton: `.tekton/tasks.yml`
  - cleanup task (deletes files from WORKSPACE_SOURCE_PATH)
  - Run unit tests with nose

### API endpoints
- `GET /health`
- `GET /accounts`
- `POST /accounts`
- `GET /accounts/{id}`
- `PUT /accounts/{id}`
- `DELETE /accounts/{id}`
