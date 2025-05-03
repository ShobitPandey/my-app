# CI/CD Pipeline with GitHub Actions, Docker & Minikube

This project demonstrates a complete CI/CD pipeline using **GitHub Actions**, **Docker**, and **Minikube**. It builds a simple Flask app, runs tests, builds a Docker image, pushes it to Docker Hub, and deploys it locally using Kubernetes on Minikube.

---

## 🚀 Project Structure

```bash
my-app/
│
├── app.py                # Flask application
├── requirements.txt      # Python dependencies
├── Dockerfile            # Builds image for the app
├── docker-compose.yml    # for local development
├── deployment.yaml       # Kubernetes Deployment & Service
├── .github/
│   └── workflows/
│       └── ci-cd.yml     # GitHub Actions workflow
