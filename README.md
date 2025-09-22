# Node.js CI/CD with Jenkins + Docker

This repo contains a simple Node.js app deployed via a CI/CD pipeline using Jenkins and Docker.

## Pipeline Stages
1. Checkout code from GitHub
2. Install dependencies
3. Run tests
4. Build Docker image
5. Push image to DockerHub

## Setup Instructions
- Configure Jenkins with Node.js and Docker
- Add DockerHub credentials in Jenkins (ID: `dockerhub`)
- Create a Pipeline job → point to this repo → Jenkinsfile will run automatically






