First, clone the repository to your local, then
For deployig mongo on the kubernetes run the following command:
` kubectl apply -f . -n <namespace> `
For Accessing the mongoDB, We have to deploy a load balancer switch to mongoLB directory and run the below command:
` kubectl apply -f mongolb.yml -n <namespace> `

