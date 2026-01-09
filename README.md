# DevOps CI/CD Demo Project 🚀

## Overview
Beginner-friendly DevOps workflow:
- Flask web app
- Dockerized
- CI/CD with GitHub Actions
- Image pushed to Docker Hub
- Deployed on Ubuntu Server with Docker Compose

## Architecture
1. Push code to GitHub
2. GitHub Actions runs tests and builds Docker image
3. Image pushed to Docker Hub
4. Server pulls image and runs container

## Quick Start
- Local: `docker-compose up`
- CI/CD: push to `main` branch
- Server: `docker-compose pull && docker-compose up -d`

## Next Steps
- Add tests
- Add monitoring (Prometheus/Grafana)
- Add staging environment
