# Flink K8s cluster setup


## Docker image
The image can be found
[here](https://hub.docker.com/r/wzorgdrager/flink-prometheus).


## TL;DR
```sh
kubectl apply -f all-manifests.yaml
kubectl port-forward -n monitoring service/grafana 3000:3000
```

Access Grafana Flink Dashboard on
[localhost:3000](http://localhost:3000/dashboard/db/flink-dashboard?refresh=5s&orgId=1).

Login details:

**username**: flink

**password**: flink-awesome
