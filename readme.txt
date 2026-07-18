# Production-Ready Azure Containerized Web Application with CI/CD

## Project Overview

This project demonstrates how to deploy a containerized web application to Microsoft Azure using modern cloud-native services. The application is packaged with Docker, stored in Azure Container Registry (ACR), deployed to Azure Container Apps, and automatically updated using GitHub Actions.

The goal of this project was to build a production-style deployment pipeline while gaining hands-on experience with Azure cloud services, containerization, identity management, and CI/CD automation.

---

## Architecture

```
Developer
    │
    ▼
GitHub Repository
    │
    ▼
GitHub Actions (CI/CD)
    │
    ▼
Docker Build
    │
    ▼
Azure Container Registry (ACR)
    │
    ▼
Azure Container Apps
    │
    ▼
FoodMart Web Application
```

---

## Azure Services Used

- Azure Resource Group
- Azure Container Registry (ACR)
- Azure Container Apps
- Azure Container Apps Environment
- Log Analytics Workspace
- Managed Identity
- Azure Role-Based Access Control (RBAC)

---

## Technologies

- Microsoft Azure
- Docker
- Git
- GitHub
- GitHub Actions
- Azure CLI
- HTML
- CSS
- JavaScript
- Nginx

---

## Features

- Containerized web application
- Automated CI/CD pipeline
- Docker image management with Azure Container Registry
- Secure authentication using Managed Identity
- Centralized logging with Azure Log Analytics
- Publicly accessible web application

---

## Deployment Process

1. Built the application into a Docker image.
2. Tagged the image for Azure Container Registry.
3. Pushed the image to Azure Container Registry.
4. Created an Azure Container Apps Environment.
5. Deployed the application to Azure Container Apps.
6. Configured Managed Identity and RBAC permissions.
7. Automated deployments using GitHub Actions.
8. Verified deployment and monitored logs using Azure CLI.

---

## Skills Demonstrated

- Cloud Deployment
- Docker Containerization
- Azure CLI
- Azure Container Registry
- Azure Container Apps
- GitHub Actions
- Continuous Integration
- Continuous Deployment
- Azure RBAC
- Managed Identity
- Log Monitoring

---

## Live Demo

**Application URL:**

https://foodmart-app.gentletree-927bcc1f.eastus.azurecontainerapps.io

---

## GitHub Repository

https://github.com/PASEDA-MODUPE/foodmart-azure-project

---

## Future Improvements

- Deploy the application to Azure Kubernetes Service (AKS)
- Provision infrastructure using Terraform
- Store secrets in Azure Key Vault
- Add Azure Monitor and Application Insights
- Configure a custom domain and HTTPS certificate

---

## Author

**Modupe Paseda**

Cloud Engineer | Azure | Docker | GitHub Actions