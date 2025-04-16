# Azure DevOps Hands-On Guide

This repository contains step-by-step hands-on guides for working with **Azure DevOps**, from setting up repositories and pipelines to deploying a .NET application on Azure Web App using release pipelines.

The goal of this repo is to help you quickly understand and apply core Azure DevOps concepts through practical implementation.

---

## 🔧 What’s Covered

1. **Repositories and Branches**
   - What is a repository and branch in Azure DevOps.
   - How to create and manage them.
     
2. **SSH Key Setup for Azure DevOps**
   - Steps to set up SSH access for secure communication.

3. **Setting Up a Classic Build Pipeline**
   - Creating a build pipeline to build your local .NET code.
   - Steps to compile, package, and publish artifacts.

4. **Agent Pool - Azure DevOps VM Agent Setup**
   - How to configure a custom self-hosted agent pool (if needed).

5. **Triggers in Azure DevOps**
   -  What are different types of triggers
   -  How to configure automatic pipeline triggers (e.g., branch commits)

6. **Creating an Azure Web App Setup**
   - How to provision an Azure Web App for hosting your application.
  
7. **Create Service Connection**
   - How to connect Azure DevOps with your Azure subscription securely.
   - Includes federated credentials and workload identity setup.

8. **Deploying to Azure Web App using Release Pipelines**
   - Creating a release pipeline to deploy your build artifacts.
   - Running a release and verifying deployment to Azure Web App.
     
9. **Pre-deployment and Post-deployment Conditions & Variables**
    - What & Use pre-deployment and post-deployment conditions.
    - What are variables & Implement variables scoped per stage.
    - Reuse configurations with variable groups, Successfully deploy to multiple environments (Dev & Stage).
  
10. **Artifacts Feed**
    - How to create and manage Azure Artifacts feeds.
    - How to configure build pipelines to pack and push NuGet packages.
    - How to assign permissions to avoid push errors.
    - How to select the feed for restoring packages in a build, How to use private packages inside Visual Studio via NuGet.

11. **Prerequisites for Terraform Setup with Azure**
    - Installation of pre requisites and Terraform
   
12. **Terraform Azure Resource Group Workflow**
    - Workflow of terraform (Initialize , Validate, Format, Plan, Apply, Destroy) with executions.
     
13. **Building Azure Infrastructure with Terraform using Remote Backend**
    - Terraform basic code structure explanation with resource group creation
    - How to create a storage account using terraform
    - what is terraform backend, how to implement that.
      
14. **End-to-End Terraform Deployment with Azure DevOps Pipeline**
    - Modular Project Setup
    - Backend Configuration
    - Git Integration & Deployment:
    - Azure DevOps Pipeline Execution

15. **azure-devops-sql-database-automation**
    - What is database automation, Why, How and types
    - Automated SQL Deployment: Created Azure SQL Server/Database manually, extracted DACPAC via SSMS, and imported it into a Visual Studio SQL project.
    - CI/CD Pipelines Setup: Built a CI pipeline to generate .dacpac and .sql artifacts, and a release pipeline to deploy schema (DACPAC) and data (Insert script) to Azure SQL.
    - End-to-End Success: Final release pipeline shows successful deployment of both schema and data, confirming full database automation.

16. **azure-devops-sql-database-automation(DacPac)**
    - Created an Azure SQL Server and Database manually, extracted a DACPAC (schema only) using SSMS, and imported it into a Visual Studio SQL Database Project for automation.
    - Set up CI/CD pipelines in Azure DevOps: Configured a build pipeline to generate DACPAC, and a release pipeline with two stages – schema deployment via DACPAC and data insertion via SQL script.
    - Implemented changes (new table and data insert script), pushed to Azure Repos triggering the pipelines, resulting in a successful end-to-end automated database deployment.
      
17. **Create Azure Key Vault Integration with Azure DevOps**
   - Created Azure Key Vault and securely stored db-pass as a secret.
   - Gave Azure DevOps access using access policies by linking the service principal (found via Entra ID).
   - Linked the secret in Azure DevOps library and securely used it in pipelines.
---

## 💡 Notes

- These guides assume you have a basic understanding of Git and Azure.
- Ideal for learners working with .NET applications in Azure DevOps environments.

Feel free to explore each `.md` file in order — they’re designed to be followed as a complete DevOps workflow.

---

## 📂 Folder Structure

Each `.md` file in this repo represents a self-contained hands-on topic. You can follow them sequentially or jump into the part you need.

