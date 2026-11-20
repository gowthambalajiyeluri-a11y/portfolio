# Personal Portfolio Website

## Project Overview
A personal portfolio website hosted on AWS EC2 using Docker and deployed automatically through GitHub Actions.

## Technologies Used
- HTML
- CSS
- Docker
- Nginx
- AWS EC2 (Ubuntu)
- Git and GitHub
- GitHub Actions (CI/CD)

## Architecture
1. Source code is maintained in GitHub.
2. GitHub Actions triggers automatically whenever code is pushed to the `main` branch.
3. GitHub Actions connects to the AWS EC2 instance using SSH.
4. The latest code is pulled from GitHub.
5. Docker builds a new image.
6. The application runs inside an Nginx container.

## Deployment
The portfolio website is hosted on an AWS EC2 Ubuntu instance and served through Docker.

**Application port:** 5000

**Live Website:** Add your EC2 public IP and port 5000 here.

## Features
- Responsive static portfolio website
- Docker containerization
- Automated deployment using GitHub Actions
- Cloud hosting using AWS EC2
- Nginx web server

## Author
Portfolio Project
# portfolio
