# Hospital Management Backend

## Tech Stack
- Java 17
- Spring Boot
- Maven
- Docker
- Render

## Live URL
https://hospital-backend-olti.onrender.com

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

## Deployment

### Backend Deployment on Render
- Backend successfully deployed on Render
- Application is running and accessible
- <img width="1628" height="873" alt="render-backend-running" src="https://github.com/user-attachments/assets/70d5f004-d562-43d7-9be5-26048ff99f1c" />



Pull request created successfully for evaluation 
Pull request test change.

