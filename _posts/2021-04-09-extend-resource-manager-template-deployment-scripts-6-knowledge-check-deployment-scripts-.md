---
    layout: post
    title: Extend ARM templates by using deployment scripts 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/extend-resource-manager-template-deployment-scripts/6-knowledge-check-deployment-scripts/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/extend-resource-manager-template-deployment-scripts.svg">
####  1. What are deployment scripts?


<i class='far fa-square'></i> &nbsp;&nbsp;Scripts that create a new Azure Resource Manager deployment.

<i class='far fa-square'></i> &nbsp;&nbsp;An Azure Automation feature for creating new environments.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;An Azure Resource Manager resource that can run custom scripts to extend the capabilities of template deployments.
<br />
<br />
<br />

####  2. How do deployment scripts use the managed identity?


<i class='far fa-square'></i> &nbsp;&nbsp;To impersonate the user who's doing the deployment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To run the Azure CLI or Azure PowerShell commands in the deployment script.

<i class='far fa-square'></i> &nbsp;&nbsp;To create the deployment script resource.
<br />
<br />
<br />

####  3. What are the direct ways that data can be passed to deployment scripts?


<i class='far fa-square'></i> &nbsp;&nbsp;Deployment scripts can access template parameters and variables.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Deployment script resources can be passed as arguments and access environment variables.

<i class='far fa-square'></i> &nbsp;&nbsp;Deployment scripts can only use the output of resources that they depend on.
<br />
<br />
<br />

####  4. Deployment scripts require:


<i class='far fa-square'></i> &nbsp;&nbsp;A custom container image.

<i class='far fa-square'></i> &nbsp;&nbsp;An Azure Automation environment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A storage account.
<br />
<br />
<br />
