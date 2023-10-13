
# To-Do App
## Customizable Kanban board like Task Manager

## Docker Container
```
docker login --username=ppilco
docker build  . -t ppilco/to-do-app:1.0.0
docker run --name todoapp -it -p 3000:3000 eb031e0d7eb9
docker push ppilco/to-do-app:1.0.0

docker pull ppilco/to-do-app:1.0.0
```
## K8S

```
$ aws configure
$ aws eks update-kubeconfig --name eks-grupo0 --alias eks-grupo0 --region us-east-1

$ Kubectl get nodes
$ Kubectl  get svc 
$ Kubectl create namespace  bootcampgp2
$ Kubectl get namespace
$ Kubectl apply -f deployment.yaml -n bootcampgp2
$ Kubectl  get deploy -n bootcampgp2
```
