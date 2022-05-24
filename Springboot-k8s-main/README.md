# Springboot-k8s
Springboot-k8s

1. Ensure to turn on port forwarding using kubernets-port-forwarder

2. To start everything-

kubectl apply -f ./


3. To scale up any service:-

kubectl scale --replicas=3 -f .\user-service.yml

4. To check whether user-service got scaled or not we use:-

kubectl get all

5. We Can also check for Kubernetes dashboard

minikube dashboard


6. To view hystrix dashboard :- http://localhost:9295/hystrix

7. To delete everything at once we use:-

kubectl delete -f ./