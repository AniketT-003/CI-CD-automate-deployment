# Node.js + Docker + Jenkins CI/CD

This project demonstrates a basic CI/CD pipeline using Jenkins, Docker, and Node.js.  
Whenever code is pushed to GitHub, Jenkins automatically builds a Docker image and pushes it to Docker Hub

## Project Overview
- Application: Node.js script that prints output to the console.
- Docker: Containerizes the app using a `Dockerfile`.
- Jenkins: Automates build, test, and deployment.
- Docker Hub: Stores the Docker image (`pooja8282/dummy-node-app`).

# Pipeline Steps
1. Checkout code from GitHub.
2. Install Node.js dependencies.
3. Run tests (if any).
4. Build Docker image.
5. Push image to Docker Hub.
6. Show Node.js console output in Jenkins logs.




