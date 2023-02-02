# K8_assignment

- minikube start --driver podman
- kubectl apply -f deployment.yaml 
- kubectl get deployments
- kubectl port-forward gotest-deployment-b7c99b56-5g76p 8090:8090  (curl localhost:8090 in different terminal)
- kubectl apply -f service.yaml
- kubectl get services
- kubectl get pod -o wide
- minikube start service gotest-service


Reference :  https://www.coding-bootcamps.com/blog/build-containerized-applications-with-golang-on-kubernetes.html#p1
