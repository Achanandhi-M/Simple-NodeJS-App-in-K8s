# Simple-NodeJS-App-in-K8s
Commands to be used 

kubectl get pods  (To List the pods inside the k8s Cluster)

kubectl get deploy (To List the deployments inside the k8s Cluster)

kubectl get svc (To List the Service inside the k8s Cluster)

minikube start (Used to Start a minikube cluster)

minikube status (Used to Check the Status of the cluster)

minikube service <service name> (Used to access service in the minikube)

kubectl create -f <file_name.yaml> (Used to create k8s object in the Declarative manner

kubectl apply -f <file_name.yaml>  (Used whenever any changes in the k8s object)



Deploying our custom NodeJSApplication inside k8s using k8s object "deployment" and "service"

Step 1: Start your Minikube cluster (Recommended way to get started with k8s)
![Screenshot from 2023-08-31 16-17-05](https://github.com/Achanandhi-M/Simple-NodeJS-App-in-K8s/assets/110651321/38b2fe87-cb18-4290-8680-8d1b581d7089)

Step 2: After Starting Minkube Deploy your K8s object(Deployments, Service, etc........) inside the Minikube cluster (if you want configuration code for deployment and service you can use this repo)
![Screenshot from 2023-08-31 16-18-35](https://github.com/Achanandhi-M/Simple-NodeJS-App-in-K8s/assets/110651321/e531b8ac-12f9-4f57-b80c-77119d5f7149)

Step 3: Accessing our Application through the Service object
![Screenshot from 2023-08-31 16-18-47](https://github.com/Achanandhi-M/Simple-NodeJS-App-in-K8s/assets/110651321/98c7a419-4f0f-4ea0-8d9c-c4db1abdebce)

Step 4: Access the application
![Screenshot from 2023-08-31 16-18-51](https://github.com/Achanandhi-M/Simple-NodeJS-App-in-K8s/assets/110651321/e6537dc4-d3bf-49b0-a366-56ce14b712ae)




