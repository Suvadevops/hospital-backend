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

Note: One SonarCloud PR scan job failed due to configuration issue, 
but code analysis and quality gate passed successfully.


Pull request created successfully for evaluation 
Pull request test change.

