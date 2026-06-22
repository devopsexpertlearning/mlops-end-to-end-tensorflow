# End-to-End MLOps Pipeline with TensorFlow, Kubeflow & MLflow

## Overview

This project demonstrates a complete production-style MLOps pipeline using TensorFlow, Kubeflow Pipelines, MLflow Model Registry, Docker, Kubernetes, KServe, GitHub Actions, and Jenkins.

The primary objective is to showcase the complete machine learning lifecycle—from code commit to automated model retraining.

---

## Architecture

```
Developer
    │
Git Push
    │
GitHub
    │
GitHub Actions / Jenkins
    │
Kubeflow Pipeline
    │
Data Ingestion
    │
Data Validation
    │
Data Preprocessing
    │
Feature Engineering
    │
Model Training
    │
Model Evaluation
    │
Model Validation
    │
MLflow Model Registry
    │
Deploy Dev
    │
Smoke Test
    │
Deploy Staging
    │
Integration Test
    │
Manual Approval
    │
Deploy Production
    │
KServe
    │
Monitoring
    │
Drift Detection
    │
Automatic Retraining
```

---

## Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python 3.12 |
| ML Framework | TensorFlow |
| Pipeline | Kubeflow Pipelines |
| Model Registry | MLflow |
| API | FastAPI |
| Container | Docker |
| Orchestration | Kubernetes |
| Serving | KServe |
| CI | GitHub Actions |
| CD | Jenkins |
| Monitoring | Prometheus + Grafana |
| Drift Detection | Evidently AI |
| Testing | Pytest |
| Security | Bandit + Trivy |

---

## Project Structure

The project is organized into separate modules for:

- Data Pipeline
- Model Training
- Kubeflow Components
- Model Registry
- Deployment
- Monitoring
- Testing

---

## Dataset

Iris Dataset

---

## Model

TensorFlow Neural Network Classifier

---

## Features

- Automated CI/CD
- Dockerized Training
- Kubeflow Pipeline
- MLflow Model Registry
- Multi-Environment Deployment
- KServe Inference
- Monitoring
- Drift Detection
- Automatic Retraining

---

## License

MIT License