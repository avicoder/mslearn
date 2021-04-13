---
    layout: post
    title: Automate Python deployments with Azure Pipelines - How do Azure and Azure DevOps support Python applications?
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/deploy-python/2-azure-support-python/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-devops/deploy-python.svg">
####  1. What kind of source changes will the typical Python project require in order to run on Azure?


<i class='far fa-square'></i> &nbsp;&nbsp;Python apps will need to be rewritten in C# or another .NET language before they will run properly on Azure.

<i class='far fa-square'></i> &nbsp;&nbsp;Configuration code will have to be rewritten to connect to Azure's configuration service.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No changes are required.
<br />
<br />
<br />

####  2. How does hosting Python apps on Azure differ from hosting apps built for other platforms (like .NET) on Azure?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Each app platform has its own dependencies, so developers need to be sure the Azure target they're using is configured correctly.

<i class='far fa-square'></i> &nbsp;&nbsp;Python deployments require use of Python performance and monitoring tools.

<i class='far fa-square'></i> &nbsp;&nbsp;Python deployments are limited to web sites on Azure.
<br />
<br />
<br />

####  3. What databases can a Python app deployed on Azure connect to?


<i class='far fa-square'></i> &nbsp;&nbsp;Azure SQL Database is the only option.

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Database for MySQL is the only option.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;They can connect to any database or service.
<br />
<br />
<br />
