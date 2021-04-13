---
    layout: post
    title: Manage database changes in Azure Pipelines - Design a database schema-change workflow in Azure Pipelines
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/manage-database-changes-in-azure-pipelines/2-design-database-schema-management/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-devops/manage-database-changes-in-azure-pipelines.svg">
####  1. True or false: The database connection string can be securely saved in the appsettings.json file of an ASP.NET Core web app in Azure?


<i class='far fa-square'></i> &nbsp;&nbsp;True

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;False
<br />
<br />
<br />

####  2. What does a SQL Server Data Tools project build produce?


<i class='far fa-square'></i> &nbsp;&nbsp;A SQL database

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A dacpac file that contains a SQL script of the database schema as it's defined in the database project

<i class='far fa-square'></i> &nbsp;&nbsp;A SQLDelta.sql file that contains data to insert into the database for this project
<br />
<br />
<br />

####  3. How is a build file for a SQL Server Data Tools database project useful in Azure Pipelines?


<i class='far fa-square'></i> &nbsp;&nbsp;The SqlAzureDacpacDeployment@1 task can create a database resource group based on that file.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The SqlAzureDacpacDeployment@1 task can download the file from the pipeline artifacts. It can then automatically generate a SQL script that contains any database changes that need to be made.

<i class='far fa-square'></i> &nbsp;&nbsp;The SqlAzureDacpacDeployment@1 task can connect the web app to the database.
<br />
<br />
<br />
