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

## Key Concepts

-   **Pods**: A pod is the smallest unit of deployment in Kubernetes. It is a group of one or more containers that are deployed together on the same host. Pods are used to run your applications in Kubernetes.

-   **Replica Sets**: A replica set is a group of identical pods that are used to scale your application horizontally. Replica sets ensure that a specified number of pods are running at all times.

-   **Deployments**: A deployment is a higher-level concept that manages replica sets and provides declarative updates to your pods. Deployments are used to deploy new versions of your application and to scale your application up or down.

-   **Services**: A service is an abstraction that defines a logical set of pods and a policy by which to access them. Services are used to expose your application to the outside world and to provide load balancing for your application.

-   **Namespaces**: Namespaces are used to organize your resources in Kubernetes. They provide a way to divide your cluster into multiple virtual clusters, each with its own set of resources.

-   **ConfigMaps**: ConfigMaps are used to store configuration data in Kubernetes. They provide a way to decouple your configuration from your application code.

-   **Secrets**: Secrets are used to store sensitive information in Kubernetes. They provide a way to securely store and manage your sensitive data.

-   **Persistent Volumes**: Persistent volumes are used to store data in Kubernetes. They provide a way to store data that persists across pod restarts.

-   **Persistent Volume Claims**: Persistent volume claims are used to request storage in Kubernetes. They provide a way to request storage that is bound to a persistent volume.

-   **Events**: Events are used to track the state of your resources in Kubernetes. They provide a way to monitor the health of your cluster and to troubleshoot issues.

-   **Labels and Selectors**: Labels are key-value pairs that are attached to resources in Kubernetes. They provide a way to organize and select your resources.

-   **initContainers**: initContainers are used to run initialization tasks before the main container starts. They provide a way to perform setup tasks before your application starts.

## Installation

-   **Minikube**: Minikube is a tool that makes it easy to run Kubernetes locally. It creates a single-node Kubernetes cluster on your local machine.

-   **Docker Desktop**: Docker Desktop is a tool that includes a single-node Kubernetes cluster. It is available for Windows and macOS.

-   **Kubernetes on AWS**: You can also run Kubernetes on AWS using tools like EKS (Elastic Kubernetes Service) or kops.

## Commands

-   `kubectl get nodes`: List all the nodes in the cluster
-   `kubectl get pods`: List all the pods in the cluster
-   `kubectl describe pod <pod-name>`: Describe the specified pod
-   `kubectl logs <pod-name>`: View the logs of the specified pod
-   `kubectl exec -it <pod-name> -c <container-name> -- /bin/bash`: Open a shell in the specified pod
-   `kubectl get services`: List all the services in the cluster
-   `kubectl get deployments`: List all the deployments in the cluster
-   `kubectl get namespaces`: List all the namespaces in the cluster
-   `kubectl get configmaps`: List all the configmaps in the cluster
-   `kubectl get secrets`: List all the secrets in the cluster
-   `kubectl get pv`: List all the persistent volumes in the cluster
-   `kubectl get pvc`: List all the persistent volume claims in the cluster
-   `kubectl get events`: List all the events in the cluster
-   `kubectl get all`: List all the resources in the cluster
-   `watch kubectl get pods`: Watch the pods in the cluster

## BAU Commands

-   `kubectl create -f <filename>`: Apply the configuration in the specified file
-   `kubectl get replicasets`: List all the replica sets in the cluster
-   `kubectl delete pod <pod-name>`: Delete the specified pod
-   `kubectl delete replicaset <replicaset-name>`: Delete the specified replica set
-   `kubectl get deployments`: List all the deployments in the cluster
-   `kubectl delete deployment <deployment-name>`: Delete the specified deployment
