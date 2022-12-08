# helm-install-prometheus

# dowloading repo chart on chart.yaml
helm dependency build

## ---------------------
Update Complete. ⎈Happy Helming!⎈
Saving 4 charts
Downloading kube-state-metrics from repo https://prometheus-community.github.io/helm-charts
Downloading prometheus-node-exporter from repo https://prometheus-community.github.io/helm-charts
Downloading prometheus-pushgateway from repo https://prometheus-community.github.io/helm-charts
Downloading alertmanager from repo https://prometheus-community.github.io/helm-charts
## ----------------------

# install helm chart application
helm install prometheus11 . -f values.yaml 