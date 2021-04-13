---
    layout: post
    title: Build a cloud governance strategy on Azure 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-cloud-governance-strategy-azure/11-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/describe-azure-governance-methodologies.svg">
####  1. How can Tailwind Traders allow some users to control the virtual machines in each environment but prevent them from modifying networking and other resources in the same resource group or Azure subscription?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a role assignment through Azure role-based access control (Azure RBAC).

<i class='far fa-square'></i> &nbsp;&nbsp;Create a policy in Azure Policy that audits resource usage.

<i class='far fa-square'></i> &nbsp;&nbsp;Split the environment into separate resource groups.
<br />
<br />
<br />

####  2. Which is the best way for Tailwind Traders to ensure that the team deploys only cost-effective virtual machine SKU sizes?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a policy in Azure Policy that specifies the allowed SKU sizes.

<i class='far fa-square'></i> &nbsp;&nbsp;Periodically inspect the deployment manually to see which SKU sizes are used.

<i class='far fa-square'></i> &nbsp;&nbsp;Create an Azure RBAC role that defines the allowed virtual machine SKU sizes.
<br />
<br />
<br />

####  3. Which is likely the best way for Tailwind Traders to identify which billing department each Azure resource belongs to?


<i class='far fa-square'></i> &nbsp;&nbsp;Track resource usage in a spreadsheet.

<i class='far fa-square'></i> &nbsp;&nbsp;Split the deployment into separate Azure subscriptions, where each subscription belongs to its own billing department.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Apply a tag to each resource that includes the associated billing department.
<br />
<br />
<br />
