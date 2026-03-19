# Kubernetes Practice Repo (Beginner-Friendly)

This repository is intended for practicing **Kubernetes (k8s) concepts** in a simple, beginner-friendly way.

---

## 🚀 Prerequisites

Make sure you have the following installed and configured:

- Docker  
- Minikube (configured to use Docker as the driver)  
- kubectl  

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd <repo-folder>

### 2. Startup minikube
minikube start --driver=docker

### 3. Apply Kubernetes configurations
Run the YAML files in the following order:

kubectl apply -f configmap/
kubectl apply -f secret/
kubectl apply -f deployment/
kubectl apply -f services/
kubectl apply -f hpa/
