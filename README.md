# Secure Cloud Builds for CI/CD using Kubernetes and Vault

This repository contains the source code and configuration files for my **major project** titled:

**“Secure Cloud Builds for CI/CD using Kubernetes and Vault”**

## Project Overview

This project focuses on securing CI/CD pipelines in a cloud-native environment using:

- **Ephemeral Kubernetes Pods**
- **HashiCorp Vault for Dynamic Secret Management**
- **Jenkins for CI/CD Orchestration**
- **ArgoCD for GitOps-based Deployment Automation**

## Project Components

- A containerized application for deployment on **Kubernetes (K8s)**
- Jenkins configured to run on a lightweight Kubernetes distribution (**K3s**)
- **ArgoCD** deployed in the cluster to continuously **sync and deploy** application manifests from Git
- Helm charts and Kubernetes YAMLs used to manage and deploy services securely
