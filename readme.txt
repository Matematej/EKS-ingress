About this project:
This EKS demo uses INGRESS to destribute trafic across 2 different applications.

Things I learned:
Kubernetes on AWS
Service account(SA) + how it works with IAM policies
Loadbalancing and Networking on EKS

How to run:
1)Create a Kubernetes cluster
2)Create a service account with a policy for your ingress controller to be able to spin up new load balancer
3)Copy Paste the files
4)Apply by: kubectl apply -f <name of the file>
