---
    layout: post
    title: Automate Node.js deployments with Azure Pipelines - How do Azure and Azure DevOps support Node.js applications?
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/deploy-nodejs/2-azure-support-nodejs/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-devops/deploy-nodejs.svg">
####  1. What kind of source changes will the typical Node.js project require in order to run on Azure?


<i class='far fa-square'></i> &nbsp;&nbsp;Node.js apps will need to be rewritten in C# or another .NET language before they will run properly on Azure.

<i class='far fa-square'></i> &nbsp;&nbsp;Configuration code will have to be rewritten to connect to Azure's configuration service.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No changes are required.
<br />
<br />
<br />

####  2. How does hosting Node.js apps on Azure differ from hosting apps built for other platforms (like .NET) on Azure?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Each app platform has its own dependencies, so developers need to be sure the Azure target they're using is configured correctly.

<i class='far fa-square'></i> &nbsp;&nbsp;Node.js deployments require use of Node.js performance and monitoring tools.

<i class='far fa-square'></i> &nbsp;&nbsp;Node.js deployments are limited to web sites on Azure.
<br />
<br />
<br />

####  3. What databases can a Node.js app deployed on Azure connect to?


<i class='far fa-square'></i> &nbsp;&nbsp;Azure SQL Database is the only option.

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Database for MySQL is the only option.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;They can connect to any database or service.
<br />
<br />
<br />
