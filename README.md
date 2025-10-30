# Install-Minikube-chocolatey 

choco install minikube -y

#Start a local cluster :

minikube start --driver=docker

#Expected output (after a few minutes):
Done! kubectl is now configured to use "minikube" cluster and "default" namespace.

#Verify cluster status
kubectl get nodes

#Expected output:
NAME       STATUS   ROLES           AGE   VERSION
minikube   Ready    control-plane   2m    v1.31.0

#Stop or delete the cluster when done
To stop (pause resources):
minikube stop

To delete completely:
minikube delete





