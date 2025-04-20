# k8s-minikube-task
# Kubernetes Minikube Task

This repository contains the deliverables for setting up a Kubernetes cluster using Minikube.

## Steps
1. Installed Minikube, kubectl, and Docker.
2. Started Minikube cluster with `minikube start --driver=docker`.
3. Created and applied `deployment.yaml` for NGINX with 2 replicas.
4. Exposed the deployment with `service.yaml` using NodePort.
5. Scaled the deployment to 4 replicas using `kubectl scale`.
6. Verified pods, services, and logs using `kubectl get` and `kubectl describe`.

## Deliverables
- `deployment.yaml`: NGINX deployment configuration.
- `service.yaml`: NodePort service configuration.
- Screenshots:
  - `pods.png`: Output of `kubectl get pods`.
  - `services.png`: Output of `kubectl get services`.
  - `nginx-page.png`: NGINX welcome page in browser.

## Tools Used
- Minikube
- kubectl
- Docker
