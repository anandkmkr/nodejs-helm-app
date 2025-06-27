# Node.js HTML App with Helm & Kubernetes

This repository contains:
- A Node.js Docker app serving a static `index.html`
- A Helm chart to deploy it with Deployment, Service, PVC, Secret, Route, etc.

## 🚀 Build Docker Image

```bash
docker build -t your-dockerhub-user/nodejs-app .
docker push your-dockerhub-user/nodejs-app
