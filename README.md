# Kubernetes_Nginx_Docker
The Repository relates to the expose the Kubernetes service with Docker run time
STEP 1: Create an pod.yaml file and update the code as above repository


    Command: apply kubernetes command:   kubectl apply -f pod.yaml
    
    
    
STEP 2: we rewuired go bind the pod with service, Here we are using NodePort as service and we have exposed.



   Command: apply kubernetes command:   kubectl apply -f service.yaml
   
Check the kubernetes configuration with command: kubectl get all

There you can find the what service has expose and which ip and port range.

Go to web browser and hit that port number fallowed by ip address eg: 127.9.0.8:30080
                      
                      
                      Note: If you ran this configuration on local use: localhost:30080

