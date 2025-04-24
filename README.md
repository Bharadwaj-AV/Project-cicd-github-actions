# CI/CD Demo App - Docker & GitHub Actions

This is a simple web application deployed using a full CI/CD pipeline with Docker, GitHub Actions, and an EC2 instance on AWS.

## 🚀 Project Overview

This project demonstrates:
- Dockerizing a simple Nginx-based web app
- Automating test, build & push using GitHub Actions
- Deploying the Docker image on an AWS EC2 instance

## 🛠️ Tech Stack

- **Docker**
- **GitHub Actions**
- **AWS EC2**
- **Docker Hub**
- **Nginx**

## 📁 Project Structure

ci-cd-demo/ ├── index.html # Main web page ├── Dockerfile # Defines Docker image └── .github/workflows └── ci-cd.yml # GitHub Actions workflow


## 🔄 CI/CD Workflow

1. On push to the main branch:
   - GitHub Actions builds Docker image
   - Pushes image to Docker Hub (`avbharadwaj/ci-cd-demo`)
2. EC2 instance manually pulls the latest image and runs the container

## 🔗 Docker Hub

- [Docker Hub Repo](https://hub.docker.com/r/avbharadwaj/ci-cd-demo)

## 🌐 Deployed Application

- Visit: [[http://<your-ec2-public-ip>](http://<your-ec2-public-ip>) ](http://54.173.12.151:80) 

## 📸 Screenshots

| Output | Browser View |
|--------|---------------|
|  ![Screenshot 2025-04-24 182442](https://github.com/user-attachments/assets/ca6e0253-1c23-4b22-ab0d-eddd2564006a)
| !![Screenshot 2025-04-24 182516](https://github.com/user-attachments/assets/b3234e3f-b5d3-4b00-95fe-35fe928b2aee)
|

## 🙌 Author

**Bharadwaj**  
[GitHub](https://github.com/Bharadwaj-AV)

