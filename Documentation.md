# Kubernetes Hands-On Labs

[![Kubernetes](https://img.shields.io/badge/Kubernetes-✔-blue?logo=kubernetes)](https://kubernetes.io)
[![Made with YAML](https://img.shields.io/badge/Made%20with-YAML-lightgrey?logo=yaml)](https://yaml.org)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

A collection of practical Kubernetes examples to level up your k8s skills!  
Perfect for beginners and a great refresher for pros. :)

# Topics Covered

| Category             | Examples                                |
|---------------------:|-----------------------------------------|
| Multi-container Pods | Sidecar, Ambassador, Adapter patterns   |
| Volumes              | `emptyDir`, `hostPath`                  |
| Jobs & CronJobs      | One-time tasks, scheduled jobs          |
| Init Containers      | Pre-startup configurations              |

# How to Use

## Quick Start

```bash
# Deploy a sidecar pod example:
kubectl apply -f pods/multi-container/sidecar-pod.yaml
```
## Cleaning Up
```
kubectl delete -f pods/multi-container/sidecar-pod.yaml
```

## Feature Examples
- **Sidecar Pattern:** 
NGINX + BusyBox logger sharing a volume.
File: `pods/multi-container/sidecar-pod.yaml`

- **Init Containers** 
Prepares files before the main container starts.
File: `init-containers/nginx-init.yaml`

```ascii
    (\_/)  
    (•_•)  
    />💻  Happy K8s hacking!
```

## Contribute
Found a bug? Want to add more examples?

## Fork this repo 🍴
Submit a PR with your changes!
