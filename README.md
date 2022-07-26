# How To Deploy MonogDB in kubernetes Cluster
* First, clone the repository to your local
* For deployig mongo on the kubernetes run the following command: 

    kubectl apply -f kubernetes-mongodb/. -n <namespace> 
    
    # For Accessing the mongoDB, 
    
    We have to deploy a load balancer switch to mongoLB directory and run the below command: 
    
    kubectl apply -f monogoLB/mongolb.yml -n <namespace>
