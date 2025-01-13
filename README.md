# Kubernetes Pod Labs

Creating a pod ngnix image
kubectl run nginx --image=nginx
===============================================

Which node are these pods placed on:
kubectl get pods -o wide
=========================================

How many containers are in pod:
kubectl describe pod webapp
==========================================

What is the state of the container agentx in the pod webapp?
kubectl describe pod webapp
===============================================

Why do you think the container agentx in pod webapp is in error?
Run the command "kubectl describe pod webapp" and look under the events section.
====================================================================================

Deleting Pod:
kubectl delete pod webapp
==========================================================
Create redis pod with reds123 image by using yaml file

Kubectl run redis --image=redis123 --dry-run -o yaml

kubectl run redis --image=redis123 --dry-run=client -o yaml

kubectl run redis --image=redis123 --dry-run=client -o yaml > redis-definition.yaml

kubectl create -f redis.yaml

==========================================================
What is the image used to create the new pods

kubectl describe pod newpods-49k2d(Id of the port).

==============================================
Which nodes are these pods placed on?
kubectl get pods -o wide

=======================================
how many containers are there in pod webapp

kubectl get pod webapp

=====================================
what image the pod webapp is used
kubectl describe pod  webapp

=============================================
Container state checking from pod

kubectl describe pod  webapp

