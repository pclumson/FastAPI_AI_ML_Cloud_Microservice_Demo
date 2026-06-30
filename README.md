

# Cloud Demo API — FastAPI + CI/CD + Microservice


> **Purpose**:
> Demonstrates production-ready FastAPI patterns with automated CI/CD
> pipelines suitable for cloud-native deployment on AWS/Azure.

## ✨ Features

| Feature | Implementation |
|---------|----------------|
| API Framework | FastAPI 0.109+ with async endpoints |
| Validation | Pydantic v2 schema enforcement |
| Containerized | Docker + multi-stage builds |
| Orchestration | Kubernetes/Helm ready |
| CI/CD | GitHub Actions OR GitLab CI |
| Security | Non-root container, environment separation |
| Observability | Structured logging placeholders for CloudWatch/Application Insights |
| Testing | pytest + coverage >80% threshold |

## 🛠 Tech Stack

- Backend: Python 3.12, FastAPI, Uvicorn
- Containers: Docker, docker-compose
- CI/CD: GitHub Actions OR GitLab CI
- Cloud Targets: AWS (ECS/EKS), Azure (AKS)
- Infrastructure as Code: Compatible with Terraform

## 🚀 Quick Start

### Prerequisites
- Docker Desktop installed
- Python 3.12 + locally
- AWS CLI configured (for deployment section)

### Local Development

```bash
# Clone repo
git clone https://github.com/pclumson/FastAPI_AI_ML_Cloud_Microservice_Demo.git
cd FastAPI_AI_ML_Cloud_Microservice_Demo

# Run locally with hot-reload
uvicorn app.main:app --reload

# Or use Docker Compose
docker-compose up --build

# Access Swagger docs at http://localhost:8000/docs
