Stateful application on Kubernetes and Kompose

brew install kubectl 
brew install minikube
brew install kompose
kompose up
kompose convert 
kubectl apply -f frontend-service.yaml,redis-master-service.yaml,redis-slave-service.yaml,frontend-deployment.yaml,redis-master-deployment.yaml,redis-slave-deployment.yaml
minikube service frontend

Source tutorial:
https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/

