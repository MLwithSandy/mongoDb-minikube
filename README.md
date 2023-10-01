# kubernetes mongodb Manifest YAML's

## Installation
1. create mongodb by applying kustomization.yaml
   kubectl apply -k .


2. create mongo-express
    kubectl apply -f mongo-express-configmap.yaml
    kubectl apply -f mongo-express-deployment.yaml
    kubectl apply -f mongo-express-service.yaml

3. Start mongo-express
   minikube service mongo-express-service 
