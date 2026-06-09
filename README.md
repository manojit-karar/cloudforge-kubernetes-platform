# CloudForge 🚀


<p align="center">
  <h2><strong>Cloud-Native DevOps Platform built with Kubernetes, GitOps, CI/CD, and Observability</strong></h2>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white">
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white">
  <img src="https://img.shields.io/badge/Alertmanager-E6522C?style=for-the-badge&logo=prometheus&logoColor=white">
  <img src="https://img.shields.io/badge/Docker_Hub-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Completed-success">
  <img src="https://img.shields.io/badge/GitOps-ArgoCD-orange">
  <img src="https://img.shields.io/badge/CI/CD-GitHub%20Actions-blue">
  <img src="https://img.shields.io/badge/Observability-Prometheus%20%7C%20Grafana-red">
</p>

---

## 📖 Overview

CloudForge is a cloud-native DevOps platform that demonstrates modern software delivery practices using **Kubernetes**, **GitHub Actions**, **Docker Hub**, **ArgoCD**, **Prometheus**, **Grafana**, and **Alertmanager**.

The project implements an end-to-end automated deployment workflow, enabling containerized applications to move seamlessly from source code to production-ready Kubernetes environments while maintaining observability and GitOps-driven deployment management.

---

## ✨ Key Features

* 🚀 Multi-node Kubernetes cluster using Kind
* 🐳 Containerized Flask application
* ⚙️ GitHub Actions CI pipeline
* 📦 Automated Docker image publishing to Docker Hub
* 🔄 GitOps-based Continuous Delivery using ArgoCD
* 📊 Prometheus monitoring and metrics collection
* 📈 Grafana dashboards and visualization
* 🚨 Alertmanager integration for alert processing
* ♻️ Self-healing Kubernetes workloads
* 🔍 End-to-end observability and monitoring

---

## 🏗️ Architecture

<p align="center">
  <img src="screenshots/architecture.png" alt="CloudForge Architecture" width="1000">
</p>

---

## 🔄 Deployment Workflow

```text
Developer
    │
    ▼
 GitHub Repository
    │
    ▼
 GitHub Actions
    │
(Build & Push Image)
    ▼
 Docker Hub
    │
(Pull Image)
    ▼
 Kubernetes Cluster (Kind)
    ▲
    │
 GitOps Sync
    │
 ArgoCD
```

---

## 🛠️ Tech Stack

| Category               | Technologies      |
| ---------------------- | ----------------- |
| Programming Language   | Python (Flask)    |
| Containerization       | Docker            |
| Container Registry     | Docker Hub        |
| Orchestration          | Kubernetes (Kind) |
| Continuous Integration | GitHub Actions    |
| GitOps                 | ArgoCD            |
| Monitoring             | Prometheus        |
| Visualization          | Grafana           |
| Alerting               | Alertmanager      |
| Version Control        | Git & GitHub      |

---

## 📂 Repository Structure

```text
CloudForge
│
├── app/
│   ├── app.py
│   ├── requirements.txt
│   └── Dockerfile
│
├── kubernetes/
│   ├── deployment.yaml
│   └── service.yaml
│
├── monitoring/
│
├── screenshots/
│   ├── architecture.png
│   ├── github-actions-success.png
│   ├── dockerhub-repository.png
│   ├── argocd-dashboard.png
│   ├── grafana-dashboard.png
│   ├── prometheus-targets.png
│   └── k8s-running-pods.png
│
├── .github/
│   └── workflows/
│       └── ci-cd.yml
│
└── README.md
```

---

## 🚀 CI Pipeline

The Continuous Integration workflow automatically:

* Detects source code changes
* Builds a Docker image
* Publishes the image to Docker Hub

### GitHub Actions Pipeline

<p align="center">
  <img src="screenshots/github-actions-success.png" alt="GitHub Actions Pipeline" width="1000">
</p>

---

## 🔄 GitOps Continuous Delivery

ArgoCD continuously monitors the Git repository and automatically synchronizes Kubernetes resources whenever changes are detected.

### ArgoCD Dashboard

<p align="center">
  <img src="screenshots/argocd-dashboard.png" alt="ArgoCD Dashboard" width="1000">
</p>

---

## 📦 Docker Hub Integration

Container images are automatically built and published to Docker Hub through GitHub Actions.

### Docker Hub Repository

<p align="center">
  <img src="screenshots/dockerhub-repository.png" alt="Docker Hub Repository" width="1000">
</p>

---

## ☸️ Kubernetes Deployment

Application workloads are managed through Kubernetes Deployments and Services.

### Running Pods

<p align="center">
  <img src="screenshots/k8s-running-pods.png" alt="Running Kubernetes Pods" width="1000">
</p>

---

## 📊 Monitoring & Observability

CloudForge includes a complete observability stack to monitor infrastructure and application performance.

### Components

| Tool         | Purpose                         |
| ------------ | ------------------------------- |
| Prometheus   | Metrics Collection & Monitoring |
| Grafana      | Visualization & Dashboards      |
| Alertmanager | Alert Routing & Management      |

### Grafana Dashboard

<p align="center">
  <img src="screenshots/grafana-dashboard.png" alt="Grafana Dashboard" width="1000">
</p>

### Prometheus Targets

<p align="center">
  <img src="screenshots/prometheus-targets.png" alt="Prometheus Targets" width="1000">
</p>

---

## 📈 Project Outcomes

* Automated application build and deployment workflows
* Reduced manual deployment effort using GitOps automation
* Implemented centralized monitoring and observability
* Established automated synchronization between GitHub and Kubernetes
* Built a reproducible cloud-native deployment platform
* Implemented a complete CI/CD and GitOps workflow

---

## 🎯 Skills Demonstrated

* Kubernetes Administration
* Docker Containerization
* GitOps
* Continuous Integration & Delivery
* Monitoring & Observability
* Infrastructure Automation
* Container Orchestration
* Linux Operations
* Cloud-Native Architecture
* DevOps Best Practices

---

## 🏆 Resume Highlights

* Built a cloud-native DevOps platform using Kubernetes, GitHub Actions, Docker Hub, ArgoCD, Prometheus, Grafana, and Alertmanager.
* Implemented GitOps-based deployment automation using ArgoCD.
* Designed an observability stack for infrastructure and application monitoring.
* Automated container build and delivery workflows through GitHub Actions and Docker Hub.
* Deployed and managed containerized workloads in a multi-node Kubernetes environment.

---

## 🚀 Future Enhancements

* Infrastructure provisioning using Terraform
* Helm chart packaging and deployment
* Multi-environment deployments (Dev, Staging, Production)
* AWS EKS migration
* Canary deployments
* Blue-Green deployment strategy
* Advanced alerting integrations

---

## 👨‍💻 Author

**Manojit Karar**

