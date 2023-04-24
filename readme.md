# Running frontend:

```
kubectl port-forward deployment.apps/client-deployment 3000:80
```

# Running backend:

```
kubectl port-forward deployment.apps/server-deployment 8000:8000
```
