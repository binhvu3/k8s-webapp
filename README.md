# MongoDB Kubernetes Deployment

This repository contains the configuration files for deploying a MongoDB instance on a Kubernetes cluster.

## Contents

- [Prerequisites](#prerequisites)
- [Usage](#usage)

## Prerequisites

Before deploying MongoDB, ensure you have the following installed:

- Kubernetes cluster (Minikube or any other Kubernetes environment)
- Kubectl (Kubernetes command-line tool)

## Usage
Start service and check ip address
```
minikube start
kubctl apply -f [###.yaml]
minikube ip
```
Check conponents
```
kubectl get node
kubectl get pod
kubectl get svc
kubectl get all
```
Clean up
```
kubectl stop
```

[TechWorld with Nana - Kubernetes Crash Course](https://www.youtube.com/watch?v=s_o8dwzRlu4)

