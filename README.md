# cortex-demo

A self-contained demo site of cortex solution

```bash
> git clone https://github.com/yltsaize/cortex-demo.git
> cd cortext-demo
> helm dependency build
> kubectl create namespace cortex
> helm install --namespace cortex cortex .

# minio-console
> kubectl port-forward svc/minio-console 9001:9001

# grafana
> kubectl port-forward svc/grafana 3000:80

# prometheus
> kubectl port-forward svc/prometheus 9090:80
```

