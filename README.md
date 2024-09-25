1. Developed a nodejs app
2. Installed docker and minikube 
3. Built a multidtage Docker and pushed it to public repository
4. Created K8 manifests deployment.yaml, service.yaml with type LoadBalancer and hpa.yaml
5. Applied the manifest files
6. Gave necessary permission to the instance that is running my minikube cluster to integrate with aws load balancer
7. now the application is available at http://a4dd5d63b1f944b96ada3032a9a5d5ae-970784770.ap-south-1.elb.amazonaws.com/
