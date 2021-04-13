---
    layout: post
    title: Implement CI/CD with Azure DevOps 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/implement-ci-cd-azure-devops/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/implement-ci-cd-azure-devops.svg">
####  1. What does the CD in CI/CD mean?


<i class='far fa-square'></i> &nbsp;&nbsp;Continuous Delivery

<i class='far fa-square'></i> &nbsp;&nbsp;Continuous Deployment

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Both are correct
<br />
<br />
<br />

####  2. What sort of pipeline is required in Azure DevOps for creating artifacts used in releases?


<i class='far fa-square'></i> &nbsp;&nbsp;An Artifact pipeline

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A Build pipeline

<i class='far fa-square'></i> &nbsp;&nbsp;A Release pipeline
<br />
<br />
<br />

####  3. What steps are required to authorize Azure DevOps to connect to and deploy notebooks to a staging or production Azure Databricks workspace?


<i class='far fa-square'></i> &nbsp;&nbsp;Create an Azure Active Directory application, copy the application ID, then use that as the Databricks bearer token in the Databricks Notebooks Deployment step of the Release pipeline

<i class='far fa-square'></i> &nbsp;&nbsp;In the production or staging Azure Databricks workspace, enable Git integration to Azure DevOps, then link to the Azure DevOps source code repo

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a new Access Token within the user settings in the production Azure Databricks workspace, then use the token as the Databricks bearer token in the Databricks Notebooks Deployment step of the Release pipeline
<br />
<br />
<br />
