
# Two-Tier Web Application with Docker & Jenkins CI/CD (Work in Progress)

This project demonstrates a production-style setup of a two-tier web application using:

  Frontend: Nginx
  Backend: Python Flask (or Node.js)
  Containerization: Docker
  CI/CD Pipeline: Jenkins
  Infrastructure: AWS (Planned)

## Project Status
Currently setting up:
- Project structure
- Dockerfiles for frontend & backend
- Jenkins pipeline architecture

Upcoming:
- Multi-container setup using Docker Compose
- Jenkins Declarative Pipeline
- Auto-build & deploy pipeline

## Tech Stack
- Docker
- Jenkins
- GitHub Webhooks
- Nginx (Frontend)
- Flask / Node.js (Backend)
- AWS (ECR + EC2 planned)

## Folder Structure (Planned)


two-tier-webapp/
│ 
├── frontend/
│ └── Dockerfile
│
├── backend/
│ └── Dockerfile
│
└── Jenkinsfile 


## Purpose
This project replicates a real industry scenario where cloud engineers deploy two-tier applications using containerization and CI/CD automation.

