# DevOps Project: Flask App CI/CD with Kubernetes & Monitoring

## 🚀 Overview
A complete DevOps pipeline for a simple Flask web application. This project demonstrates containerization, automated CI/CD, and real-time monitoring using Prometheus and Grafana.

## 🧠 Skills Demonstrated
- Docker & DockerHub
- GitHub Actions for CI/CD
- Kubernetes (Deployment + Service)
- Monitoring with Prometheus & Grafana

## 🧱 Stack
- Python + Flask
- Docker
- GitHub Actions
- Kubernetes
- Prometheus & Grafana

## 📁 Project Structure
```
.
├── app.py
├── requirements.txt
├── Dockerfile
├── k8s-deployment.yaml
└── .github/
    └── workflows/
        └── deploy.yml
```

## 🛠 How to Run
1. Build & Push Docker Image:
```bash
docker build -t your-dockerhub/flask-app .
docker push your-dockerhub/flask-app
```

2. Apply Kubernetes Resources:
```bash
kubectl apply -f k8s-deployment.yaml
```

3. Configure Prometheus to scrape metrics.

## 🎯 Value
Demonstrates a real-world DevOps pipeline with full automation, deployment, and monitoring — a key requirement for production environments.
