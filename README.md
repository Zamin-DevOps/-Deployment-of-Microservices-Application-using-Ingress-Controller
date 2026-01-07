🚀 Deployment of Microservices Application using Ingress Controller
by Sayyed Zamin Abbas








🛠️ Project Overview

This project demonstrates a production-grade deployment of a multi-page microservices-based web application on AWS EKS using an NGINX Ingress Controller and a complete Jenkins CI/CD pipeline.

The project focuses on:

Containerizing applications using Docker

Orchestrating services using Kubernetes (EKS)

Implementing Ingress for path-based routing

Automating build and deployment using Jenkins

🔧 Tools Used
Category	Tools
Version Control	

CI/CD	

Containers	

Orchestration	

Monitoring	

GitOps	
📐 Architecture Overview

Multiple microservices deployed as separate Kubernetes Deployments

Each service exposed internally using ClusterIP Services

NGINX Ingress Controller handles external traffic routing

Path-based routing configured for each microservice

Jenkins pipeline automates build, push, and deployment

⚙️ CI/CD Pipeline Flow

Developer pushes code to GitHub

Jenkins pipeline triggers automatically

Docker images are built and pushed to registry

Kubernetes manifests are applied to EKS cluster

Ingress routes traffic to the respective microservices

📂 Project Structure (Sample)
.
├── service-1/
│   ├── Dockerfile
│   └── deployment.yaml
├── service-2/
│   ├── Dockerfile
│   └── deployment.yaml
├── ingress/
│   └── ingress.yaml
├── Jenkinsfile
└── README.md




📌 Author

Sayyed Zamin Abbas
DevOps Enthusiast | DevOps | Cloud & Kubernetes Learner
