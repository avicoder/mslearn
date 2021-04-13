---
    layout: post
    title: Create production workloads on Azure Databricks with Azure Data Factory 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-production-workloads-azure-databricks-azure-data-factory/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/create-production-workloads-azure-databricks-azure-data-factory.svg">
####  1. What's the purpose of linked services in Azure Data Factory?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To represent a data store or a compute resource that can host execution of an activity

<i class='far fa-square'></i> &nbsp;&nbsp;To represent a processing step in a pipeline

<i class='far fa-square'></i> &nbsp;&nbsp;To link data stores or computer resources together for the movement of data between resources
<br />
<br />
<br />

####  2. How can parameters be passed into an Azure Databricks notebook from Azure Data Factory?


<i class='far fa-square'></i> &nbsp;&nbsp;Use the new API endpoint option on a notebook in Databricks and provide the parameter name

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use notebook widgets to define parameters that can be passed into the notebook

<i class='far fa-square'></i> &nbsp;&nbsp;Deploy the notebook as a web service in Databricks, defining parameter names and types
<br />
<br />
<br />

####  3. What happens to Databricks activities (notebook, JAR, Python) in Azure Data Factory if the target cluster in Azure Databricks isn't running when the cluster is called by Data Factory?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;If the target cluster is stopped, Databricks will start the cluster before attempting to execute

<i class='far fa-square'></i> &nbsp;&nbsp;The Databricks activity will fail in Azure Data Factory – you must always have the cluster running

<i class='far fa-square'></i> &nbsp;&nbsp;Simply add a Databricks cluster start activity before the notebook, JAR, or Python Databricks activity
<br />
<br />
<br />
