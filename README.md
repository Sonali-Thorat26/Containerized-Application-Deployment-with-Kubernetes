# Kubernetes Apache Deployment Project

This project demonstrates the deployment of a containerized Apache application using Kubernetes (Minikube).

## 🚀 Commands Performed:

- **Start Cluster:** `minikube start --driver=docker`
- **Deploy App:** `kubectl create deployment apache-app --image=httpd:latest`
- **Scaling:** `kubectl scale deployment apache-app --replicas=3`
- **Expose Service:** `kubectl expose deployment apache-app --type=NodePort --port=80`
- **View Result:** `minikube service apache-app`

## 🛠 Technologies Used:

- Docker
- Kubernetes (Minikube)
- Apache (httpd)
