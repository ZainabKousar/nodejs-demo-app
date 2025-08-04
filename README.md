# 🚀 CI/CD Pipeline for Node.js App using GitHub Actions & Docker

## 📌 Project Summary
This project showcases the automation of building and deploying a Node.js web application through a CI/CD pipeline, utilizing *GitHub Actions* and *Docker* for seamless integration and delivery.

## 🛠 Tasks Completed
- Developed a basic Node.js application with Express.js.
- Created a Dockerfile to containerize the application.
- Included a .dockerignore file to reduce image size and improve build efficiency.
- Uploaded the complete project to GitHub.
- Defined a CI/CD workflow (.github/workflows/main.yml) to:
  - Install project dependencies
  - Build a Docker image
  - Push the image to DockerHub upon changes to the main branch
- Set up GitHub Secrets for secure DockerHub authentication.

## 📦 Outcome
With every new push to the main branch:
- A new Docker image is automatically built.
- The image is pushed to the linked DockerHub repository without manual intervention.

## 🔧 Tools & Technologies
- Node.js
- Express.js
- Docker
- GitHub Actions
- DockerHub
