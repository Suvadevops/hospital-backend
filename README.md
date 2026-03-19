# 🏥 Hospital Management Backend

Backend service for the Hospital Management System built using Spring Boot.  
Handles patient data, appointments, and REST API operations.

---
## 🛠 Tech Stack

- ☕ Java 17  
- 🌱 Spring Boot  
- 📦 Maven  
- 🐳 Docker  
- ☁️ Render  
- ☁️ Microsoft Azure  

---
## 🚀 Live API

- 🌍 Render (Primary Backend):  
  👉 https://hospital-backend-olti.onrender.com  

- ☁️ Azure Deployment (Secondary):  
  👉 https://hospital-backend-app57.azurewebsites.net/patients  

---

## Build & Run (Local)
mvn clean package -DskipTests
java -jar target/*.jar

## Docker
docker build -t hospital-backend .
docker run -p 8080:8080 hospital-backend

## SonarCloud & CI

- SonarCloud analysis executed via GitHub Actions
- Quality Gate: PASSED
- Docker image build: SUCCESS
- <img width="1917" height="926" alt="sonar-passed" src="https://github.com/user-attachments/assets/b77b6aa9-774b-4b9c-bcd7-6bef17dbce14" />


Note: One SonarCloud PR scan job failed due to configuration issue, 
but code analysis and quality gate passed successfully.

## Deployment on Render

- Backend successfully deployed on Render
- Application is running and accessible
- <img width="1628" height="873" alt="render-backend-running" src="https://github.com/user-attachments/assets/70d5f004-d562-43d7-9be5-26048ff99f1c" />


🚀 Deployment on Azure
This project is successfully deployed on Microsoft Azure using Docker containers.

🔹 Services Used
Azure App Service (Linux)
Azure Container Registry (ACR)

Docker
🔹 Backend Deployment
Docker image built and pushed to Azure Container Registry

Deployed using Azure Web App (Linux container)

Live Backend API:
👉 https://hospital-backend-app57.azurewebsites.net/patients
<img width="1917" height="379" alt="Screenshot 2026-03-20 000711" src="https://github.com/user-attachments/assets/75c69d44-d966-4ddd-9679-123d2217048f" />






Pull request created successfully for evaluation 
Pull request test change.

