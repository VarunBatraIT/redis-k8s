# How to setup

```bash
kubectl create -f configmap.yaml
kubectl create -f deployment.yaml
kubectl get all
```

# How to verified

```bash
kubectl run -it --rm --image=redis --restart=Never redis-client-example -- redis-cli -h example-redis -p 6379
```