---
    layout: post
    title: Integrate Azure Databricks with Azure Synapse 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/integrate-azure-databricks-other-azure-services/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/integrate-azure-databricks-other-azure-services.svg">
####  1. What are the two prerequisites for connecting Azure Databricks with Azure Synapse Analytics that apply to the Azure Synapse Analytics instance?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a database master key and configure the firewall to enable Azure services to connect

<i class='far fa-square'></i> &nbsp;&nbsp;Use a correctly formatted ConnectionString and create a database master key

<i class='far fa-square'></i> &nbsp;&nbsp;Add the client IP address to the firewall's allowed IP addresses list and use the correctly formatted ConnectionString
<br />
<br />
<br />

####  2. Which is the correct syntax for overwriting data in Azure Synapse Analytics from a Databricks notebook?


<i class='far fa-square'></i> &nbsp;&nbsp;df.write.mode("overwrite").option("...").option("...").save()

<i class='far fa-square'></i> &nbsp;&nbsp;df.write.format("com.databricks.spark.sqldw").overwrite().option("...").option("...").save()

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;df.write.format("com.databricks.spark.sqldw").mode("overwrite").option("...").option("...").save()
<br />
<br />
<br />
