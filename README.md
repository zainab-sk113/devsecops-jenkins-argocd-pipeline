# devsecops-jenkins-argocd-pipeline
DevSecOps CI/CD Pipeline using Jenkins, Docker, Kubernetes, ArgoCD and Terraform
# DevSecOps CI/CD Pipeline

This project demonstrates a complete DevSecOps pipeline using Jenkins, Docker, Kubernetes, and GitHub.

## Tools Used

- GitHub
- Jenkins
- Docker
- Kubernetes
- SonarQube
- Trivy
- ArgoCD

## Pipeline Flow

1. Developer pushes code to GitHub
2. Jenkins triggers pipeline
3. Docker image is built
4. Security scan using Trivy
5. Image pushed to DockerHub
6. Kubernetes deployment
7. ArgoCD handles GitOps deployment

## Project Features

- Automated CI/CD pipeline
- Containerized application
- Kubernetes deployment
- Security scanning
