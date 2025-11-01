# IRIS API - CI/CD with Kubernetes

FastAPI application for IRIS flower classification with automated deployment to Google Kubernetes Engine using GitHub Actions.

## Overview

- **Build**: Docker containerization
- **Deploy**: Kubernetes on Google Cloud
- **CI/CD**: Automated with GitHub Actions
- **API**: FastAPI with Swagger UI

## Quick Start


Access: `http://localhost:8080/docs`

## Deployment

CI/CD automatically deploys on every push to main branch.


## API

| Endpoint | Method | Description |
|----------|--------|-------------|
| `/` | GET | Health check |
| `/docs` | GET | Swagger UI |
| `/predict` | POST | Predict species |

## Pod vs Container

**Docker Container**: Isolated unit running a single process.

**Kubernetes Pod**: Container wrapper that shares network and storage with other containers in the Pod.

## Technologies

- FastAPI
- Docker
- Kubernetes
- Google Cloud
- GitHub Actions
