# 🎬 Netflix Clone Project

A production-grade Netflix Clone deployed on AWS using DevSecOps practices.

## 🚀 Tech Stack

- AWS EC2 & EKS
- Docker
- Kubernetes
- Jenkins CI/CD
- SonarQube
- Trivy
- ArgoCD (GitOps)
- Prometheus & Grafana

---

# 📸 Project Screenshots

## 1. Netflix Application

![Netflix Home](screenshots/netflix-home.png)

---

## 2. Jenkins CI/CD Pipeline

![Jenkins Pipeline](screenshots/jenkins-pipeline.png)

Pipeline stages:
- Git Checkout
- SonarQube Scan
- Quality Gate
- OWASP Scan
- Trivy Scan
- Docker Build & Push
- Deploy to Kubernetes

---

## 3. ArgoCD GitOps Deployment

![ArgoCD](screenshots/argocd.png)

Application Status:
- Healthy ✅
- Synced ✅

---

## 4. Amazon EKS Cluster

![EKS Cluster](screenshots/eks-cluster.png)

Kubernetes Version: 1.34

---

## 5. AWS Security Group

![Security Group](screenshots/security-group.png)

LoadBalancer exposes the application on HTTP Port 80.

---

# ☁️ Deployment Flow

GitHub → Jenkins → SonarQube → Trivy → DockerHub → ArgoCD → Amazon EKS

---
