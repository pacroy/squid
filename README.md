# Squid Helm Chart

_based on [lifen-charts/squid](https://github.com/honestica/lifen-charts/tree/master/squid)_

## Local Installation

```sh
kubectl create namespace sunday
helm upgrade --install <release_name> . --namespace=<namespace> --values values.yaml
```

## Installation from Repository

```sh
kubectl create namespace sunday
helm repo add pacroy https://pacroy.github.io/helm-repo/
helm repo update
helm upgrade --install <release_name> pacroy/squid --namespace=<namespace> --values values.yaml
```
