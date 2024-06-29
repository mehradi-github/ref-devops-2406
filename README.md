# CI/CD with Kubernetes, Docker

- [CI/CD with Kubernetes, Docker](#cicd-with-kubernetes-docker)
  - [Prerequisites](#prerequisites)
    - [Adding a Submodule](#adding-a-submodule)
    - [Installing Docker ](#installing-docker-)
    - [Kubernetes Cluster installation using minikube](#kubernetes-cluster-installation-using-minikube)
  - [Set up Ingress on Minikube with the NGINX Ingress Controller](#set-up-ingress-on-minikube-with-the-nginx-ingress-controller)
  - [Skaffold](#skaffold)

## Prerequisites

### [Adding a Submodule](https://github.com/mehradi-github/microservices-ticketing?tab=readme-ov-file#adding-a-submodule)

### [Installing Docker ](https://github.com/mehradi-github/ref-devops-flow?tab=readme-ov-file#installing-docker-on-ubuntu-2204-lts)

### [Kubernetes Cluster installation using minikube](https://github.com/mehradi-github/ref-devops-flow?tab=readme-ov-file#kubernetes-cluster-installation-using-minikube)

## Set up Ingress on Minikube with the NGINX Ingress Controller

An [Ingress](https://kubernetes.io/docs/tasks/access-application-cluster/ingress-minikube/) is an API object that defines rules which allow external access to services in a cluster. An Ingress controller fulfills the rules set in the Ingress.

```sh
minikube addons enable ingress
kubectl get pods -n ingress-nginx
```

## Skaffold

[Skaffold](https://github.com/mehradi-github/microservices-ticketing?tab=readme-ov-file#skaffold) handles the workflow for building, pushing and deploying your application, allowing you to focus on what matters most: writing code.
