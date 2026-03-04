# Minikube MongoDB Orchestration Stack

A professional Kubernetes implementation of a containerized **MongoDB** database and **Mongo-Express** web-based administration interface, orchestrated on a local **Minikube** cluster.

## 🏗️ Architectural Overview
This project demonstrates the core principles of Kubernetes resource management and Infrastructure as Code (IaC):
- **Stateful Application Deployment**: Managing MongoDB instances using K8s Deployments.
- **Security & Configuration**: Decoupling sensitive credentials using **Kubernetes Secrets** and environment-specific data via **ConfigMaps**.
- **Service Networking**: 
  - **ClusterIP**: For internal secure communication between Mongo-Express and MongoDB.
  - **NodePort**: To expose the Mongo-Express GUI for external browser access.

## 🛠️ Tech Stack
- **Orchestration**: Kubernetes (Minikube)
- **Database**: MongoDB 6.0
- **UI/Management**: Mongo-Express
- **Tooling**: kubectl, Docker

