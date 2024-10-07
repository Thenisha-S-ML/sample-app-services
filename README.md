# sample-app-services

Practicing kubernetes services like ClusterIP, NodepORT, loadBalancer, Ingress

# steps 

1. Create a deployment file with nginx
2. Create a clusterip yaml file
      - apply 
      - check the service by creating a temporary pod 
3. Create a NodePort yaml file
      - apply
      - checking the accessibilty from nodeport
4. Create a LoadBalancer yaml file
      - apply
      - checking the service available by ip
5. Create a Ingress yaml file
      - apply
      - taking the minikube ip trying accessing the web page avaialble (using curl or wget)
