# Jenkins CI/CD Pipeline with GitHub Integration

## Project Overview
Complete end-to-end CI/CD pipeline deployed on AWS EC2 
using Jenkins, GitHub Webhooks, Docker and Linux.

## What I Implemented
- Deployed and configured Jenkins on AWS EC2 Ubuntu instance
- Integrated GitHub repository with Jenkins using Webhooks
- Automated build triggers on every GitHub push
- Containerized Node.js application using Docker
- Successfully executed 4+ automated pipeline builds
- Managed complete source code using Git and GitHub

## Tools and Technologies Used

| Tool | Purpose |
|------|---------|
| Jenkins | CI/CD pipeline automation |
| AWS EC2 | Cloud server — Ubuntu instance |
| Docker | Application containerization |
| GitHub | Source code management |
| Webhooks | Automated build triggers |
| Linux/Ubuntu | Server operating system |
| Terraform | Infrastructure as Code |
| Kubernetes | Container orchestration |

## Project Architecture
```
GitHub Push → Webhook Trigger → Jenkins Pipeline 
→ Docker Build → Container Deploy on AWS EC2
```

## Jenkins Pipeline Stages
1. Code Checkout from GitHub repository
2. Build Docker image from Dockerfile
3. Run Docker container on port 8000
4. Application deployed successfully

## How to Run Locally
```bash
git clone https://github.com/shu-kate/node-todo-cicd
npm install
node app.js
docker build -t node-todo-app .
docker run -d -p 8000:8000 node-todo-app
docker-compose up
```

## Project Screenshots

### Jenkins Pipeline — Build Success
![Pipeline Success](https://github.com/shu-kate/node-todo-cicd/raw/master/Screenshot%202026-03-17%20112819.png)

### Jenkins Console Output — GitHub Integration
![Console Output](https://github.com/shu-kate/node-todo-cicd/raw/master/Screenshot%202026-03-17%20112912.png)

### Jenkins Build — Finished SUCCESS
![Build Success](https://github.com/shu-kate/node-todo-cicd/raw/master/Screenshot%202026-03-17%20113908.png)

### GitHub Auto Trigger — Webhook Working
![GitHub Trigger](https://github.com/shu-kate/node-todo-cicd/raw/master/Screenshot%202026-03-17%20113104.png)

### Docker Container Running on AWS EC2
![Docker Running](https://github.com/shu-kate/node-todo-cicd/raw/master/Screenshot%202026-03-17%20113143.png)

## Connect With Me
- LinkedIn: https://linkedin.com/in/shubhangi-kate04
- GitHub: https://github.com/shu-kate
- Email: shubhangikate999@gmail.com
