# Installation
```shell
NAMESPACE=loki
helm repo add grafana https://grafana.github.io/helm-charts
helm install promtail -n ${NAMESPACE} -f values.yaml grafana/promtail --version 6.15.3 --wait
```