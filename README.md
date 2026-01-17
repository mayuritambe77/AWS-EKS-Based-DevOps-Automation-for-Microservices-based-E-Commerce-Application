## AWS EKS-Based DevOps Automation for Microservices E-Commerce Application

## 📌 Project Overview

This project demonstrates an **end-to-end DevOps implementation** for a **microservices-based E-commerce application** using modern cloud-native tools and practices. The application is based on the **OpenTelemetry E-Commerce Demo**, which follows a real-world microservices architecture with services developed in multiple programming languages.

The primary goal of this project is to **design, automate, and deploy** a production-like application using **containerization, Infrastructure as Code, CI/CD, Kubernetes orchestration, and GitOps principles** on **AWS EKS**.

## 🏗️ Architecture Overview

* Multi-microservice architecture with frontend, backend, and supporting services
* Containerized services using Docker
* Kubernetes-based deployment on AWS EKS
* Infrastructure provisioned using Terraform with a modular approach
* CI using GitHub Actions and CD using Argo CD (GitOps)

## 🛠️ Technologies Used

* **Cloud**: AWS (EC2, EKS, IAM, VPC, Load Balancers, Route 53)
* **Containerization**: Docker, Docker Compose
* **Container Orchestration**: Kubernetes (EKS)
* **Infrastructure as Code**: Terraform (Modules, Remote Backend with S3, State Locking with DynamoDB)
* **CI/CD**: GitHub Actions (CI), Argo CD (CD – GitOps)
* **Languages**: Java, Go
* **Networking & Exposure**: Kubernetes Services (ClusterIP, LoadBalancer), DNS integration using Route 53

## 🚀 Key Features & Implementations

* Containerized multiple microservices using Docker and managed images via Docker Hub
* Provisioned AWS EKS cluster within a custom VPC using Terraform modules
* Implemented Kubernetes Deployments and Services for scaling, self-healing, and service discovery
* Built CI pipelines using GitHub Actions for a Java-based microservice to automate build and image creation
* Implemented GitOps-based continuous deployment using Argo CD to deploy Kubernetes manifests
* Exposed frontend service securely using Kubernetes LoadBalancer and integrated a custom domain via Route 53

## 📈 Learning Outcomes

* Hands-on experience with **real-world microservices DevOps workflows**
* Practical understanding of **Kubernetes orchestration and AWS EKS**
* Strong foundation in **Terraform-based Infrastructure as Code**
* Experience implementing **CI/CD and GitOps** for cloud-native applications
* Improved understanding of **AWS networking and security concepts**

## 📂 Repository Structure (Example)
.
├── docker/                  # Dockerfiles for microservices
├── kubernetes/               # Kubernetes manifests
├── terraform/                # Terraform IaC for EKS and VPC
├── .github/workflows/        # GitHub Actions CI pipelines
└── README.md

## ✅ Conclusion
This project showcases a **production-grade DevOps workflow** for deploying and managing a cloud-native, microservices-based E-commerce application on AWS. It highlights practical DevOps skills including automation, orchestration, infrastructure management, and continuous delivery using industry-standard tools.


