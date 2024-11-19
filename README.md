# two containers on single pod
# step 1
Create one instance in ubuntu 
select instance type as t2 medium
go the root user by cmd sudo su -
And update  by using cmd apt update -y
Installation of docker,minikube and  kubectl
minikube : it is used create one node in a cluster
kubectl : kubectl is the command-line interface (CLI)
# create a yml file
by using cmd vi tom.yml
![Screenshot 2024-11-19 165640](https://github.com/user-attachments/assets/2a5927cd-8f7a-4ea9-b5ab-ddfd8256e8b6)
using cmd kubectl create -f tom.yml
to see the pods using kubectl get pods
![Screenshot 2024-11-19 165504](https://github.com/user-attachments/assets/c275625c-ff8d-4b50-8185-a5666ae47644)

