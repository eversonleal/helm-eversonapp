# Helm - Everson App Deploy on K8s Cluster

Helm Chart to Deploy Everson App, it uses luksa/kubia:1.2 Docker Image.

## Installation

Clone this repo

## Usage
1. Install chart into the K8s cluster:

```bash
helm install eversonapp helm-eversonapp/ --values helm-eversonapp/values.yaml
```

2. Everything magically done.
