End-to-End DevOps Workflow: Deploying a GenAI Mental Health Assistant

A production-ready AI-powered Mental Health Assistant Chatbot designed using Flask, Google Gemini, and LangChain. This project is focused on highlighting end-to-end DevOps practices including CI/CD automation, containerization, and deployment.

🚀 Project Objective:-

Deploy and manage the application using best DevOps practices in a cloud environment.

Build an intelligent chatbot that addresses mental health-related queries empathetically and informatively.

Architecture Diagram - <img width="3680" height="2760" alt="image" src="https://github.com/user-attachments/assets/f743ae2c-7479-43f9-921f-b78dfdf093b0" />

⚙️ Technologies Used:-

Application Stack:

Flask: Python web framework for backend

LangChain: Framework for integrating LLMs

Google Gemini: For natural language generation

PostgreSQL: Database for user and chat history

Docker: Containerization

DevOps Stack:

Ansible: Configuration management of EC2 instance

Docker Compose: Multi-container orchestration

Jenkins: CI/CD pipeline

GitHub: Source code and CI/CD trigger

Docker Hub: Container image registry

Nginx: Reverse proxy and static file serving

🧰 Key DevOps Highlights:-

CI/CD Pipeline (Jenkins):

Steps in pipeline:

1 Clone the code from Github

2 Owasp Dependency Scan

3 Sonarqube Scan for Code Quality Check

4 Build Docker Image

5 Push image to Docker Hub

6 SSH into EC2 Instance

7 Pull Docker Image form Docker Hub

8 Run container using Docker Compose

Containerization & Deployment:

The app is containerized using Docker.

docker-compose.yaml defines the services:

Flask app

PostgreSQL

Nginx reverse proxy

🎮 Features of the Chatbot:-

Empathetic and professional tone in responses

User login and chat history storage

🚀 Future Improvements:-

Add monitoring using Prometheus + Grafana

🌐 Live URL:-

http://13.127.230.86

📊 Author

Jayesh Thorat

DevOps Enthusiast | AWS Certified Solutions Architect
