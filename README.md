# kubernetes_basic
# Kubernetes Basic Project

# Overview
This project demonstrates the fundamentals of deploying and managing applications on a local Kubernetes cluster using Minikube. It covers the essential Kubernetes concepts such as creating deployments, exposing services, scaling applications, and viewing logs using kubectl.

# Objective
The main goal is to gain hands-on experience with Kubernetes basics by setting up a local cluster and deploying a sample application (Nginx) to understand how Kubernetes manages containerized apps.

# Tools Used
Minikube: For running a Kubernetes cluster locally.
kubectl: Command-line tool to interact with Kubernetes clusters.
Docker: To pull and run container images.

# Project Structure
The project contains the following important files:

deployment.yaml : Defines the deployment for the Nginx application, including the number of replicas and container specifications.
service.yaml : Exposes the deployed application via a Kubernetes Service to allow external access.
Any other scripts or configuration files needed to run the deployment.

# Key Steps Executed
Setup Minikube: Installed and started a Minikube cluster locally.
Create Deployment: Used deployment.yaml to deploy the Nginx app with multiple replicas.
Expose Service: Created a Kubernetes Service using service.yaml to expose the app on a NodePort.
Verify Deployment: Used kubectl get pods and kubectl describe to check pod status and details.
Scale Deployment: Scaled the number of replicas using kubectl scale command.
Logs Inspection: Viewed container logs using kubectl logs to troubleshoot and verify app behavior.

