# Reddit Clone Kubernetes Manifests

Hi! This repository comprises the Kubernetes manifests required for deploying the Reddit Clone application on a Kubernetes cluster. It includes configuration files to manage the services, deployments and other resources necessary for a robust and scalable application deployment, I'm looking for.

## Contents
- **Deployment YAMLs**: Defines the desired state of the application, including the number of replicas, container images and resource limits.
- **Service YAMLs**: Specifies how to access the Reddit Clone pods, using Kubernetes services to route traffic.
- **Ingress YAMLs**: Manages external access to the services, including URL routing and load balancing.
- **HPA YAMLs**: Horizontal Pod Autoscaler configurations to automatically scale the application based on CPU or memory usage.
- **Cluster Autoscaler YAML**: Scales the nodes up or down, based on insufficient resources for the pods, or node utilisation.

There's been a strong emphasis on high availability, scalability, performance and security of the Reddit Clone application within the Kubernetes environment. This setup aims to streamline the deployment process, facilitate continuous integration and delivery, and support efficient resource management.

## How to Use
To deploy the Reddit Clone application using these manifests, ensure you have `kubectl` configured with access to your Kubernetes cluster. Then, apply the manifests in your desired namespace:

```
kubectl apply -f <manifest_file.yaml> -n <namespace>
```

Refer to each YAML file for specific details on the configuration and customization options.

---

This repository is part of the larger Reddit Clone project, designed to demonstrate the capabilities of Kubernetes in supporting modern, scalable web applications.Reddit-Argocd

Check this out:- https://github.com/TanishkaMarrott/Orchestrating-DevSecOps-Pipeline-for-a-Cloud-Native-Architecture
