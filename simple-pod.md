# Run a quick simple pod

```bash
kubectl run simple-pod --image=nginx --port 80
kubectl get pods/simple-pod -o wide
curl 10.42.0.24
```
