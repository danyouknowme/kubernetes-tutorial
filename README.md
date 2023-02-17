# Kubernetes tutorial


[Kubernetes Crash Course for Absolute Beginnersn](https://www.youtube.com/watch?v=s_o8dwzRlu4)


### Commands

#### start the cluster
```
minikube start --driver docker
```

#### check status
```
minikube status
```

#### create resource in minikube cluster
```
kubectl apply -f <fileName>
```

#### get all components in the cluster
```
kubectl get all
```

#### get status of node
```
kubectl get node
```

#### get configmap
```
kubectl get configmap
```

#### get secret
```
kubectl get secret
```

#### get services
```
kubectl get svc
```

#### view details of the component
```
kubectl describe <resourceType> <resourceName>
```

#### view logs of container
```
kubectl logs <podName>
```

#### get minikube ip address
```
minikube ip
```

#### stop the cluster
```
minikube stop
```
