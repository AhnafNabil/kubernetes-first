# kubernetes-first

### Get Pods
```bash
kubectl get pod
```

### Config yaml
```bash
kubectl apply -f mongo-config.yaml
```
```bash
kubectl apply -f mongo-secret.yaml
```
```bash
kubectl apply -f mongo.yaml 
```
```bash
kubectl apply -f webapp.yaml
```

### Run webapp in browser

1. Makesure minikube is running 
2. Check using "minikube status"

```bash
minikube ip
```
```bash
ip:webapp-nodePort
```


