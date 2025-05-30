# CI/CD Pipeline: Flask + Docker + Jenkins + Kubernetes

This is a simple CI/CD project deploying a Flask app to Kubernetes via Jenkins. 

Happy to publish my first CI/CD project :)

## Components

- **Flask App**
- **Dockerfile**
- **Jenkins Pipeline**
- **Kubernetes Deployment**

## Setup

1. **Build locally**:
   ```bash
   docker build -t flask-app .
   docker run -p 5000:5000 flask-app
