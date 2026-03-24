# DevOps Project

This project demonstrates a simple Dockerized web application deployed on AWS EC2.

## Steps:
- Created HTML file
- Created Dockerfile
- Built Docker image
- Ran container on EC2
- Accessed via public IP

## Tools:
- AWS EC2
- Docker
- GitHub

## Project Flow
GitHub → Docker Build → EC2 Deployment → Public IP Access

## How to Run
1. Build Docker image:
   docker build -t devops-project .

2. Run container:
   docker run -d -p 8085:80 devops-project

3. Access in browser:
   http://<EC2-PUBLIC-IP>:8085
