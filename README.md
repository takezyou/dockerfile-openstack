# dockerfile-openstack
## How to install Kubernetes

```
# Kubernetes for Mac
$ brew cask install minikube
```

## How to running and check Kubernetes

```
# Running
$ minikube start

# Check
$ minikube status
```

## Check Dashboard URL

```
$ minikube service list
```

## Deployment Excute

```
$ kubectl apply -f k8s/queens-deployment.yaml
```

## Show Deployment,Pod,replicaset

```
kubectl get deployment,replicaset,pod -o wide
```
