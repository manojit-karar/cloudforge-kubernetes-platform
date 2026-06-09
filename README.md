\# CloudForge 🚀



<p align="center">

&#x20; <img src="screenshots/architecture.png" alt="CloudForge Architecture" width="1000">

</p>



<p align="center">

&#x20; <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge\&logo=kubernetes\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/GitHub\_Actions-2088FF?style=for-the-badge\&logo=github-actions\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge\&logo=argo\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge\&logo=prometheus\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge\&logo=grafana\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/Alertmanager-E6522C?style=for-the-badge\&logo=prometheus\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/Docker\_Hub-2496ED?style=for-the-badge\&logo=docker\&logoColor=white" />

&#x20; <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white" />

</p>



<p align="center">

&#x20; <strong>Cloud-Native DevOps Platform implementing Kubernetes, CI/CD, GitOps, and Observability</strong>

</p>



<p align="center">

&#x20; <img src="https://img.shields.io/badge/Status-Completed-success" />

&#x20; <img src="https://img.shields.io/badge/Project-CloudForge-blue" />

&#x20; <img src="https://img.shields.io/badge/GitOps-ArgoCD-orange" />

&#x20; <img src="https://img.shields.io/badge/CI/CD-GitHub%20Actions-purple" />

</p>



\---



\## 📌 Overview



CloudForge is a cloud-native DevOps platform designed to demonstrate modern application deployment and operational practices using Kubernetes, GitOps, CI/CD automation, and observability tooling.



The project automates the complete software delivery lifecycle from source code commit to Kubernetes deployment while providing monitoring, visualization, and automated synchronization capabilities.



\---



\## 🎯 Key Highlights



\* Built a multi-node Kubernetes platform using Kind

\* Implemented CI pipelines using GitHub Actions

\* Automated container image publishing to Docker Hub

\* Established GitOps-based Continuous Delivery with ArgoCD

\* Designed an observability stack using Prometheus, Grafana, and Alertmanager

\* Implemented self-healing Kubernetes workloads and service discovery

\* Automated end-to-end deployment workflow from Git push to Kubernetes synchronization



\---



\## 🏗 Architecture



<p align="center">

&#x20; <img src="screenshots/architecture.png" alt="Architecture Diagram" width="1000">

</p>



\---



\## 🛠 Tech Stack



| Category         | Technologies      |

| ---------------- | ----------------- |

| Language         | Python (Flask)    |

| Containerization | Docker            |

| Orchestration    | Kubernetes (Kind) |

| CI/CD            | GitHub Actions    |

| GitOps           | ArgoCD            |

| Monitoring       | Prometheus        |

| Visualization    | Grafana           |

| Alerting         | Alertmanager      |

| Registry         | Docker Hub        |

| Version Control  | Git \& GitHub      |



\---



\## 🔧 Core Components



| Component      | Purpose                      |

| -------------- | ---------------------------- |

| GitHub         | Source code management       |

| GitHub Actions | Continuous Integration       |

| Docker Hub     | Container registry           |

| ArgoCD         | GitOps Continuous Delivery   |

| Kubernetes     | Container orchestration      |

| Prometheus     | Metrics collection           |

| Grafana        | Visualization and dashboards |

| Alertmanager   | Alert processing             |

| Flask          | Sample application workload  |



\---



\## 📂 Project Structure



```text

CloudForge

│

├── app

│   ├── app.py

│   ├── requirements.txt

│   └── Dockerfile

│

├── kubernetes

│   ├── deployment.yaml

│   └── service.yaml

│

├── monitoring

│

├── screenshots

│   ├── architecture.png

│   ├── grafana-dashboard.png

│   ├── prometheus-targets.png

│   ├── github-actions-success.png

│   ├── dockerhub-repository.png

│   ├── argocd-dashboard.png

│   └── k8s-running-pods.png

│

├── .github

│   └── workflows

│       └── ci-cd.yml

│

└── README.md

```



\---



\## 🔄 End-to-End Workflow



1\. Developer pushes code to GitHub

2\. GitHub Actions builds Docker image

3\. Docker image is pushed to Docker Hub

4\. ArgoCD detects repository changes

5\. Kubernetes manifests are synchronized

6\. Kubernetes deploys updated workloads

7\. Prometheus collects cluster metrics

8\. Grafana visualizes infrastructure and application metrics

9\. Alertmanager processes and routes alerts



\---



\## 🚀 CI Pipeline



GitHub Actions automatically:



1\. Detects code changes

2\. Builds a Docker image

3\. Pushes the image to Docker Hub



\### GitHub Actions Pipeline



<p align="center">

&#x20; <img src="screenshots/github-actions-success.png" alt="GitHub Actions Pipeline" width="1000">

</p>



\---



\## 🚢 GitOps Continuous Delivery



ArgoCD continuously monitors the Git repository and automatically synchronizes Kubernetes resources whenever changes are detected.



```text

GitHub Repository

&#x20;       │

&#x20;       ▼

&#x20;     ArgoCD

&#x20;       │

&#x20;       ▼

&#x20;Kubernetes Cluster

```



\### ArgoCD Dashboard



<p align="center">

&#x20; <img src="screenshots/argocd-dashboard.png" alt="ArgoCD Dashboard" width="1000">

</p>



\---



\## 📦 Docker Hub Integration



Docker images are automatically published to Docker Hub through GitHub Actions.



\### Docker Hub Repository



<p align="center">

&#x20; <img src="screenshots/dockerhub-repository.png" alt="Docker Hub Repository" width="1000">

</p>



\---



\## ☸ Kubernetes Deployment



Application workloads are deployed and managed through Kubernetes Deployments and Services.



\### Running Pods



<p align="center">

&#x20; <img src="screenshots/k8s-running-pods.png" alt="Kubernetes Running Pods" width="1000">

</p>



\---



\## 📊 Monitoring \& Observability



CloudForge includes a complete observability stack for monitoring infrastructure and application performance.



\### Prometheus



\* Metrics collection

\* Cluster monitoring

\* Resource utilization tracking



\### Grafana



\* Dashboard visualization

\* Infrastructure monitoring

\* Performance analysis



\### Alertmanager



\* Alert routing

\* Alert processing

\* Notification management



\### Grafana Dashboard



<p align="center">

&#x20; <img src="screenshots/grafana-dashboard.png" alt="Grafana Dashboard" width="1000">

</p>



\### Prometheus Targets



<p align="center">

&#x20; <img src="screenshots/prometheus-targets.png" alt="Prometheus Targets" width="1000">

</p>



\---



\## 📈 Project Outcomes



\* Automated application build and deployment workflows

\* Reduced manual deployment effort through GitOps automation

\* Implemented centralized monitoring and observability

\* Enabled automatic reconciliation of Kubernetes resources using ArgoCD

\* Established a reproducible cloud-native deployment platform

\* Built a complete CI/CD and GitOps workflow from source code to deployment



\---



\## 🏆 Skills Demonstrated



\* Kubernetes Administration

\* Docker Containerization

\* GitOps

\* CI/CD

\* Infrastructure Monitoring

\* Observability

\* Container Orchestration

\* Linux Operations

\* DevOps Practices

\* Cloud-Native Architecture



\---



\## 🎯 Key Learning Outcomes



\* Kubernetes workload orchestration

\* Container lifecycle management

\* GitOps deployment methodologies

\* CI/CD pipeline implementation

\* Monitoring and observability practices

\* Cloud-native application deployment

\* Kubernetes troubleshooting and debugging

\* Infrastructure automation concepts



\---



\## 🚀 Future Enhancements



\* Terraform-based infrastructure provisioning

\* Helm chart packaging

\* Multi-environment deployments (Dev / Staging / Production)

\* AWS EKS migration

\* Canary deployments

\* Blue-Green deployment strategy

\* Advanced alerting integrations



\---



\## 📌 Resume Highlights



\* Built a cloud-native DevOps platform using Kubernetes, GitHub Actions, Docker Hub, ArgoCD, Prometheus, Grafana, and Alertmanager.

\* Implemented GitOps workflows for automated Kubernetes deployment synchronization.

\* Designed observability solutions for monitoring infrastructure and application health.

\* Automated container build and delivery pipelines using GitHub Actions and Docker Hub.

\* Deployed and managed containerized workloads in a multi-node Kubernetes environment.



\---



\## 👨‍💻 Author



\*\*Manojit Karar\*\*



Cloud Engineer | DevOps Enthusiast | Kubernetes \& Cloud Technologies



