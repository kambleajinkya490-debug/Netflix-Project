
# 🎬 Netflix Clone Project

A production-grade Netflix Clone deployed on AWS using DevSecOps practices. This project demonstrates an end-to-end CI/CD pipeline with automated security scanning, containerization, Kubernetes deployment, GitOps, and monitoring.

---

##  Tech Stack

- **Cloud:** AWS EC2, Amazon EKS
- **CI/CD:** Jenkins
- **Containerization:** Docker
- **Orchestration:** Kubernetes
- **GitOps:** ArgoCD
- **Code Quality:** SonarQube
- **Security:** Trivy, OWASP Dependency Check
- **Monitoring:** Prometheus, Grafana
- **Frontend:** React + Vite

---

##  Project Architecture

GitHub → Jenkins → SonarQube → OWASP → Trivy → DockerHub → ArgoCD → Amazon EKS → Prometheus & Grafana

---

## Features

- Automated CI/CD pipeline using Jenkins
- Static code analysis with SonarQube
- Vulnerability scanning using Trivy
- Docker image build and push to DockerHub
- GitOps deployment with ArgoCD
- Kubernetes deployment on Amazon EKS
- Monitoring with Prometheus and Grafana
- LoadBalancer service for external access

---

##  CI/CD Pipeline Stages

1. Clean Workspace
2. Checkout Source Code
3. SonarQube Analysis
4. Quality Gate Validation
5. Install Dependencies
6. OWASP Dependency Scan
7. Trivy File System Scan
8. Docker Build & Push
9. Kubernetes Deployment
10. Continuous Sync using ArgoCD

---

##  AWS Infrastructure

| Service | Purpose |
|---------|---------|
| EC2 | Jenkins & DevSecOps Tools |
| Amazon EKS | Kubernetes Cluster |
| DockerHub | Container Registry |
| ELB | Application Exposure |

---

##  Monitoring

- Prometheus for metrics collection
- Grafana dashboards for visualization
- Node Exporter for node-level metrics

---

##  Security

- SonarQube code quality analysis
- OWASP dependency vulnerability scan
- Trivy container & filesystem scan
- Kubernetes deployment best practices

---

##  Repository Structure

```text
Netflix-Project/
├── Kubernetes/
├── src/
├── public/
├── Dockerfile
├── package.json
├── vite.config.ts
├── README.md
└── screenshots/
```

---

##  Deployment

```bash
# Clone repository
git clone <your-repository-url>

# Build Docker image
docker build -t netflix .

# Deploy to Kubernetes
kubectl apply -f Kubernetes/
```

---

##  Result

- CI/CD pipeline completed successfully
- Application deployed on Amazon EKS
- GitOps synchronization through ArgoCD
- Monitoring enabled with Prometheus & Grafana

---

