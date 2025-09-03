# CUExaminer


CUExaminer is a full-stack web application built to enhance the academic experience for 700+ Carleton University students.  
It provides an intuitive interface, secure backend, and scalable deployment environment for managing exams, courses, and academic data.

---

## Features
- Full-Stack Implementation:  
  - Backend: [Spring Boot](https://spring.io/projects/spring-boot) (RESTful API)  
  - Database: [PostgreSQL](https://www.postgresql.org/)  
  - Frontend: [ReactJS](https://react.dev/)  
- Containerized Deployment: Dockerized backend and frontend for seamless portability and scalability.  
- Faster Deployment: Reduced deployment time by 30 seconds using optimized container workflows.  
- Reliable API Testing: Validated with 200+ Postman tests for stability and correctness.  

---

## Tech Stack
- Frontend: ReactJS, JavaScript, HTML/CSS  
- Backend: Spring Boot, Java  
- Database: PostgreSQL  
- Containerization: Docker  
- Testing: Postman  

---

## Project Structure
CUExaminer/
│── backend/ # Spring Boot REST API
│── frontend/ # ReactJS client
│── database/ # SQL migrations, schema, seed data
│── docker-compose.yml
│── README.md

---

## Getting Started

### Prerequisites
- [Docker](https://www.docker.com/) installed  
- [PostgreSQL](https://www.postgresql.org/) (if running locally without Docker)  
- [Node.js](https://nodejs.org/) (for React development mode)  

### Clone the Repository
```bash
git clone https://github.com/Abdullah-Shibib/CUExaminer.git
cd CUExaminer
Run with Docker
docker-compose up --build
This will:

Start PostgreSQL database

Run Spring Boot backend

Launch ReactJS frontend

Run Locally (without Docker)

Start PostgreSQL and configure application.properties in the backend.

Run the Spring Boot server:
cd backend
./mvnw spring-boot:run
Start the React frontend:
cd frontend
npm install
npm start
Testing

API Testing: All backend endpoints are tested with 200+ Postman test cases.

Run tests with:

newman run CUExaminer.postman_collection.json
Results

Enhanced academic experience for 700+ Carleton University students.

Deployment time reduced by 30 seconds through Docker containerization.

200+ API tests ensure high reliability and performance.

Contributing

Contributions, issues, and feature requests are welcome.
Feel free to fork the repo and submit a pull request.

Link to Backend code down below:
https://github.com/abaan-noman/carleton-examiner-backend
