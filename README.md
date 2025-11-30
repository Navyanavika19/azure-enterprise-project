# azure-enterprise-project
“End-to-end Azure Cloud &amp; DevOps enterprise project featuring Terraform IaC, AKS, Helm, CI/CD automation, cloud governance, monitoring, and migration workflows.”
re Enterprise Cloud Project (Terraform + AKS + CI/CD)

This repository contains an end-to-end enterprise-grade cloud project built on Microsoft Azure.  
It includes infrastructure provisioning using Terraform, application deployment using Kubernetes & Helm,  
CI/CD automation using GitHub Actions and Azure DevOps, and full monitoring, governance, and lifecycle documentation.

## 📁 Repository Structure

```text
azure-enterprise-project/
│── terraform/
│    ├── modules/
│    │   ├── vnet/
│    │   ├── aks/
│    │   ├── appservice/
│    │   ├── keyvault/
│    │   └── loganalytics/
│    ├── env/
│    │   ├── dev/
│    │   ├── test/
│    │   └── prod/
│── kubernetes/
│    ├── helm/
│    │   ├── backend/
│    │   ├── frontend/
│    │   ├── ingress/
│── ci-cd/
│    ├── github-actions/
│    └── azure-devops/
│── migration/
│── modernization/
│── monitoring/
│── governance/
│── docs/

🎯 Project Goals

Provision complete Azure infrastructure using Terraform IaC

Deploy microservices on Azure Kubernetes Service (AKS)

Implement Helm charts for backend & frontend

Create automated pipelines using GitHub Actions + Azure DevOps

Integrate Azure Monitor, Log Analytics, Application Insights

Follow enterprise-level governance, security & cost optimization

Provide real-world migration + modernization documentation

🛠️ Tech Stack

Azure (AKS, VNets, App Services, Key Vault, Log Analytics)

Terraform + modules structure

Kubernetes + Helm

GitHub Actions / Azure DevOps Pipelines

Containerization with Docker

Azure Policy, RBAC, NSGs, Key Vault

Monitoring & Observability

📘 Documentation

All detailed steps, architectures, migration plans, and runbooks are available inside the docs/ folder.


