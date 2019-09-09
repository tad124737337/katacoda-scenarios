Use the below command to start a simple demo application

`kubectl create deployment hello-node --image=gcr.io/hello-minikube-zero-install/hello-node`{{execute}}

Then expose it using

`kubectl expose deployment hello-node --type=LoadBalancer --port=8080`{{execute}}

