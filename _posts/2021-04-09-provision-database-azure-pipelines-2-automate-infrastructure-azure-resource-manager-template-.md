---
    layout: post
    title: Provision databases in Azure Pipelines - Automate infrastructure deployment by using Azure Resource Manager templates
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/provision-database-azure-pipelines/2-automate-infrastructure-azure-resource-manager-template/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-devops/provision-database-azure-pipelines.svg">
####  1. Azure Key Vault is a good place to store what kind of information?


<i class='far fa-square'></i> &nbsp;&nbsp;Passwords only.

<i class='far fa-square'></i> &nbsp;&nbsp;API keys only.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Anything that needs tight control over who has access to it.
<br />
<br />
<br />

####  2. Where can you get an Azure Resource Manager template that already has some common infrastructure declared?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A quickstart template from the quickstart template gallery.

<i class='far fa-square'></i> &nbsp;&nbsp;Stack Overflow template repository.

<i class='far fa-square'></i> &nbsp;&nbsp;You must start with an empty JSON file and construct the template.
<br />
<br />
<br />

####  3. How can an Azure Resource Manager template access a secret in the key vault?


<i class='far fa-square'></i> &nbsp;&nbsp;The template file can access the key vault directly.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The parameter file can access the key vault secret and create a parameter for the template to use.

<i class='far fa-square'></i> &nbsp;&nbsp;The key vault can inject secrets into the template with a KeyVault@1 task.
<br />
<br />
<br />
