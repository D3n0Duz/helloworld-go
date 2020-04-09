# helloworld-go

### Docker
```
docker build -t helloworld-go:latest .
```

```
docker run -it -p 8080:8080 helloworld-go
```

```
docker tag helloworld-go docker.io/d3n0/helloworld-go
```

```
docker push docker.io/d3n0/helloworld-go
```

### Minikube
```
minikube start --vm-driver virtualbox
```

```
minikube dashboard
```

### Kubernetes

```
kubectl create -f service.yaml
```

```
kubectl create -f deployment.yaml
```

```
minikube stop
```

```
minikube destroy
```