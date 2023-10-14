
# To-Do App
## Customizable Kanban board like Task Manager

## Docker Container
```
docker login --username=ppilco
docker build  . -t ppilco/to-do-app:2.0.0
docker run --name todoapp -it -p 3000:3000 ppilco/to-do-app:2.0.0
docker push ppilco/to-do-app:2.0.0

docker pull ppilco/to-do-app:2.0.0
```
## K8S

```
$ aws configure
$ aws eks update-kubeconfig --name eks-grupo0 --alias eks-grupo0 --region us-east-1

$ Kubectl get nodes
$ Kubectl  get svc 
$ Kubectl create namespace  grupo2
$ Kubectl get namespace
$ Kubectl apply -f deployment.yaml -n grupo2
$ Kubectl  get deploy -n grupo2
```
pipe2