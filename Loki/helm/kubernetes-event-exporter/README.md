# Installation
```shell
NAMESPACE=kube-system
helm repo add bitnami https://charts.bitnami.com/bitnami
helm install kubernetes-event-exporter -n ${NAMESPACE} -f values.yaml bitnami/kubernetes-event-exporter --version 2.8.3 --wait
```