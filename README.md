# 🚀 CI/CD HTML Docker Deployment

A simple CI/CD project where an HTML website is containerized using Docker and automatically deployed to an AWS EC2 server using GitHub Actions.

## 🛠️ Technologies Used

- HTML
- Docker
- Docker Compose
- Git & GitHub
- GitHub Actions
- AWS EC2
- Nginx
- SSH

---

## 📁 Project Structure

cicd-html-docker/
├── index.html
├── Dockerfile
├── docker-compose.yml
├── .gitignore
├── .github/
│   └── workflows/
│       └── deploy.yml
├── screenshots/
└── README.md

---

## Step 1 - Create HTML Website

Created a simple HTML website using VS Code.

📸 **Screenshot:** `screenshots/index-html.png`

---

## Step 2 - Create Dockerfile

Created a Dockerfile using Nginx to containerize the HTML website.

📸 **Screenshot:** `screenshots/dockerfile.png`

---

## Step 3 - Create Docker Compose

Created `docker-compose.yml` to build and run the website container.

📸 **Screenshot:** `screenshots/docker-compose.png`

---
## Step 4 - Create .gitignore

Created a `.gitignore` file to prevent sensitive and unnecessary files from being pushed to GitHub.

📸 **Screenshot:** `screenshots/gitignore.png`

---
## Step 5 - Build and Run Docker Container

Built the Docker image and started the container using Docker Compose.

Checked the running container using Docker commands.

📸 **Screenshot:** `screenshots/docker-build-run.png`

---
## Step 6 - Push Project to GitHub

Created a Git repository and pushed the project files to GitHub.

📸 **Screenshot:** `screenshots/git-push.png`

---
## Step 7 - Prepare EC2 Server

Launched an Ubuntu EC2 instance and connected to the server using SSH.

Installed and configured Docker and Docker Compose on the EC2 server.

📸 **Screenshot:** `screenshots/ec2-docker-install.png`

---

## Step 8 - Test Website on EC2

Accessed the deployed website using the EC2 public IP and configured port.

📸 **Screenshot:** `screenshots/website-ec2.png`

---

## Step 8 - Configure GitHub Actions

Created a GitHub Actions workflow for automatic deployment to the EC2 server.

📸 **Screenshot:** `screenshots/deploy-yaml.png`

---

## Step 9 - Configure GitHub Secrets

Added the required EC2 SSH credentials as GitHub repository secrets.

📸 **Screenshot:** `screenshots/github-secrets.png`

---

## Step 10 - GitHub Actions Deployment

Pushed changes to the `main` branch.

GitHub Actions automatically connected to the EC2 server and deployed the updated application.

📸 **Screenshot:** `screenshots/github-actions-success.png`

---

## Step 11 - Verify Deployment

Verified that the updated website was successfully running inside the Docker container on EC2.

📸 **Screenshot:** `screenshots/final-website.png`

---

## 🔄 CI/CD Workflow

Git Push  
↓  
GitHub  
↓  
GitHub Actions  
↓  
SSH → EC2  
↓  
Docker Build  
↓  
Docker Compose  
↓  
Nginx Container  
↓  
Updated Website

---

## 🎯 What I Learned

- AWS EC2 deployment
- Docker containerization
- Docker Compose
- Git & GitHub
- GitHub Actions
- SSH-based deployment
- CI/CD automation
- Nginx web server
- Linux server management

---

## 👨‍💻 Author

**Prince Tyagi**

AWS Cloud | Linux | Docker | CI/CD | Networking | Cybersecurity
