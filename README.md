# Squid Helm Chart

_based on [lifen-charts/squid](https://github.com/honestica/lifen-charts/tree/master/squid)_

## Local Installation

```sh
helm install <release_name> . --namespace=<namespace> --values values.yaml
```

## Installation from Repository

```sh
helm repo add pacroy https://pacroy.github.io/helm-repo/
helm repo update
helm install <release_name> pacroy/bookstack --namespace=<namespace> --values values.yaml
```
