# Kubernetes Learning for Beginners

## What is Kubernetes?

Kubernetes is an open-source container orchestration platform that automates the deployment, scaling, and management of containerized applications. It was originally designed by Google and is now maintained by the Cloud Native Computing Foundation.

## Why Kubernetes?

Kubernetes is a powerful tool that can help you manage your containerized applications. It provides a number of benefits, including:

-   Scalability: Kubernetes makes it easy to scale your applications up or down based on demand.
-   High availability: Kubernetes can automatically restart containers that fail, ensuring that your applications are always available.
-   Resource management: Kubernetes can help you manage the resources used by your applications, ensuring that they have the right amount of CPU and memory available.
-   Self-healing: Kubernetes can automatically detect and replace containers that are not working correctly.
-   Service discovery and load balancing: Kubernetes can help you manage the network traffic to your applications, ensuring that they are always available and responsive.

## Commands

-   `kubectl get nodes`: List all the nodes in the cluster
-   `kubectl get pods`: List all the pods in the cluster
-   `kubectl get services`: List all the services in the cluster
-   `kubectl get deployments`: List all the deployments in the cluster
-   `kubectl get namespaces`: List all the namespaces in the cluster
-   `kubectl get configmaps`: List all the configmaps in the cluster
-   `kubectl get secrets`: List all the secrets in the cluster
-   `kubectl get pv`: List all the persistent volumes in the cluster
-   `kubectl get pvc`: List all the persistent volume claims in the cluster
-   `kubectl get events`: List all the events in the cluster
-   `kubectl get all`: List all the resources in the cluster

## BAU Commands

-   `kubectl create -f <filename>`: Apply the configuration in the specified file
-   `kubectl get replicasets`: List all the replica sets in the cluster
-   `kubectl delete pod <pod-name>`: Delete the specified pod
-   `kubectl delete replicaset <replicaset-name>`: Delete the specified replica set
