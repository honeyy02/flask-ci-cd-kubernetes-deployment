# Flask CI/CD Kubernetes Deployment 🚀

## 📌 Overview
This project demonstrates an end-to-end CI/CD pipeline using Jenkins to build, containerize, and deploy a Flask application to Kubernetes.

---

## 🚀 Workflow

1. Source Code Checkout (GitHub)
2. Build Docker Image
3. Run Docker Container
4. Push Image to Docker Hub
5. Deploy to Kubernetes (K3s)

---

## 🛠️ Tech Stack
- Python (Flask)
- Docker
- Jenkins
- Kubernetes (K3s)
- Docker Hub

---

## 📂 Project Structure
```
├── app/
├── docker/
├── k3s_config.yaml
├── Jenkinsfile
```

---

## 🔄 Jenkins Pipeline Stages
- Checkout
- Docker Build
- Docker Run
- Docker Login
- Docker Push
- Deployment (Kubernetes)

---

## 🐳 Docker Image
```
honeyy02/login-python
```

---

## ☸️ Kubernetes Deployment
- Deployment + Service (NodePort)
- Uses ConfigMap & Secret for environment variables

---

## 📌 Key Learnings
- CI/CD pipeline creation using Jenkins
- Containerization using Docker
- Image management with Docker Hub
- Kubernetes deployment automation
