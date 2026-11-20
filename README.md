# Personal Portfolio Website

## Project Overview
A personal portfolio website hosted on AWS EC2 using Docker and automated deployment through GitHub Actions.

## Technologies Used
- HTML
- CSS
- Docker
- Nginx
- AWS EC2 (Ubuntu)
- Git and GitHub
- GitHub Actions (CI/CD)

## Project Architecture
1. Source code is maintained in GitHub.
2. GitHub Actions triggers when code is pushed to the main branch.
3. GitHub Actions connects to the EC2 instance using SSH.
4. The latest source code is pulled from GitHub.
5. Docker builds a new image.
6. The website runs inside an Nginx Docker container.

## Features
- Personal portfolio website
- Responsive web design
- Docker containerization
- Automated CI/CD deployment
- AWS cloud hosting
- Nginx web server

## Deployment Details
- Cloud Platform: AWS EC2
- Operating System: Ubuntu
- Containerization: Docker
- Web Server: Nginx
- Application Port: 5000
- CI/CD: GitHub Actions

## How to Run Locally
```bash
docker build -t portfolio-img .
docker run -d -p 5000:80 --name portfolio-container portfolio-img
```

## Author
Portfolio Project
