# Terraform AWS EKS Cluster

This project uses Terraform to provision a Kubernetes (EKS) cluster on AWS.

## 📁 Project Structure

- `main.tf`: Defines EKS cluster and IAM roles
- `provider.tf`: Sets AWS provider and region
- `variables.tf`: Input variables for cluster config
- `outputs.tf`: Useful outputs like cluster name and endpoint

## 🚀 How to Use

```bash
terraform init
terraform plan
terraform apply
