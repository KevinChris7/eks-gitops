# EKS with GitOps and Monitoring
This project demonstrates how to set up a GitOps pipeline on Amazon EKS using ArgoCD, and integrate Prometheus and Grafana for Kubernetes cluster monitoring. The goal is to provide an automated deployment pipeline and real-time monitoring for your Kubernetes applications.

# Prerequisites
Before you begin, make sure you have the following tools installed:

AWS CLI: For interacting with AWS services.
kubectl: Kubernetes command-line tool to manage your EKS cluster.
Helm: A package manager for Kubernetes.
git: For version control and interacting with GitHub.
Additionally, you’ll need:

An EKS cluster set up and running.
ArgoCD installed on your EKS cluster.
A GitHub repository to store your Kubernetes manifests and configurations.
