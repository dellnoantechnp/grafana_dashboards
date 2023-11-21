# Installation
```shell
NAMESPACE=loki
helm repo add grafana https://grafana.github.io/helm-charts
helm install loki -n ${NAMESPACE} -f values.yaml grafana/loki-distributed --version 0.69.8 --wait
```