---
    layout: post
    title: Spark architecture fundamentals 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/spark-architecture-fundamentals/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/spark-architecture-fundamentals.svg">
####  1. Which notebook format is used in Databricks?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;DBC

<i class='far fa-square'></i> &nbsp;&nbsp;.notebook

<i class='far fa-square'></i> &nbsp;&nbsp;.spark
<br />
<br />
<br />

####  2. When creating a new cluster in the Azure Databricks workspace, what happens behind the scenes?


<i class='far fa-square'></i> &nbsp;&nbsp;Azure Databricks provisions a dedicated VM that processes all jobs, based on your VM type and size selection.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Azure Databricks creates a cluster of driver and worker nodes, based on your VM type and size selections.

<i class='far fa-square'></i> &nbsp;&nbsp;When an Azure Databricks workspace is deployed, you are allocated a pool of VMs. Creating a cluster draws from this pool.
<br />
<br />
<br />

####  3. To parallelize work, the unit of distribution is a Spark Cluster. Every Cluster has a Driver and one or more executors. Work submitted to the Cluster is split into what type of object?


<i class='far fa-square'></i> &nbsp;&nbsp;Stages

<i class='far fa-square'></i> &nbsp;&nbsp;Arrays

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Jobs
<br />
<br />
<br />
