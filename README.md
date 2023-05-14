# capstone_Udacity

Kubernetes cluster creation 

The k8s cluster is created using eksctl tool by passing cluster.yml which has configuration of the clsuter and the eksctl invokes the cloud formation template to create cluster.

commands : 
create clsuter 
eksctl create cluster -f cluster.yaml

delete cluster 
eksctl delete cluster --region=us-west-1 --name=clustercapstone
