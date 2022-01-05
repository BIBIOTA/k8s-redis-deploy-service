### COMMAND

```
kubectl apply -f redis-master-deployment.yaml
kubectl apply -f redis-master-service.yaml
```

## connect to redis-cli
```
kubectl exec -it redis-{pod} -- redis-cli
```

<a href="https://github.com/kubernetes">Example from Kubernetes example</a>
