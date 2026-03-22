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
# Clone repository
git clone https://github.com/shu-kate/node-todo-cicd

# Install dependencies
npm install

# Run with Node
node app.js

# Or run with Docker
docker build -t node-todo-app .
docker run -d -p 8000:8000 node-todo-app

# Or use Docker Compose
docker-compose up
```

## Project Screenshots
Jenkins Pipeline — Build Success
![Jenkins Success](add-your-screenshot-url-here)

Jenkins Dashboard — Pipeline Overview  
![Jenkins Dashboard](add-your-screenshot-url-here)

## Connect With Me
- LinkedIn: https://linkedin.com/in/shubhangi-kate04
- GitHub: https://github.com/shu-kate
- Email: shubhangikate999@gmail.com
