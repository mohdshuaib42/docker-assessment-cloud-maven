# 🚀 Docker Tasks - Flask Application

This repository contains Docker-related tasks demonstrating containerization concepts and implementations using a Python Flask application.

---

## 📌 Tasks Completed

### 1. Dockerfile for Flask Application
- Wrote a **Dockerfile** for a Python Flask application.  
- Exposed the container to **port 5000**.

### 2. Multi-Stage Docker Builds
- Implemented **multi-stage Docker builds** for a Python Flask-based **Library Management App**.  
- Optimized image size by separating **build** and **runtime** stages.  
- Added a **.dockerignore** file to exclude unnecessary files from the build context.

### 3. Docker Concepts - Image vs Container vs Volume vs Network
- **Image** → A Docker image is the blueprint/template used to create containers.  
- **Container** → A container is the running instance of an image, containing all dependencies of the application.  
- **Volume** → Volumes act like attached storage for containers, ensuring **data persistence** even if a container crashes.  
- **Network** → Docker networking defines how containers communicate with each other.  

---

## ⚙️ How to Run

### 🔹 Build the Docker Image
```bash
docker build -t flask-app .
