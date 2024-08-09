# Nginx Deployment on Minikube with GitHub Actions

This project demonstrates how to deploy an Nginx application to a Minikube cluster using GitHub Actions.

## Content

- **`k8s/deployment.yml`**: Defines the Nginx deployment in Kubernetes.
- **`k8s/service.yml`**: Defines the service to expose Nginx.
- **`.github/workflows/deploy-nginx.yml`**: GitHub Actions workflow for automating the deployment.

## Usage

1. Ensure you have `Minikube`, `kubectl` and `Docker` installed.
2. Create a GitHub Repository.
3. Configure Workflow.
4. Push changes.

## Verification

1. Check pods: Verify that the Nginx Pod is running.