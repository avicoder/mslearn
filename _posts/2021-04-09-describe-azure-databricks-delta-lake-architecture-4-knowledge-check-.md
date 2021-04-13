---
    layout: post
    title: Describe Azure Databricks Delta Lake architecture 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/describe-azure-databricks-delta-lake-architecture/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/describe-azure-databricks-delta-lake-architecture.svg">
####  1. What is a lambda architecture and what does it try to solve?


<i class='far fa-square'></i> &nbsp;&nbsp;An architecture that defines a data processing pipeline whereby microservices act as compute resources for efficient large-scale data processing

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;An architecture that splits incoming data into two paths - a batch path and a streaming path. This architecture helps address the need to provide real-time processing in addition to slower batch computations.

<i class='far fa-square'></i> &nbsp;&nbsp;An architecture that employs the latest Scala runtimes in one or more Databricks clusters to provide the most efficient data processing platform available today
<br />
<br />
<br />

####  2. What command should be issued to view the list of active streams?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Invoke spark.streams.active

<i class='far fa-square'></i> &nbsp;&nbsp;Invoke spark.streams.show

<i class='far fa-square'></i> &nbsp;&nbsp;Invoke spark.view.active
<br />
<br />
<br />

####  3. What is required to specify the location of a checkpoint directory when defining a Delta Lake streaming query?


<i class='far fa-square'></i> &nbsp;&nbsp;.writeStream.format("delta").checkpoint("location", checkpointPath) ...

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;.writeStream.format("delta").option("checkpointLocation", checkpointPath) ...

<i class='far fa-square'></i> &nbsp;&nbsp;.writeStream.format("parquet").option("checkpointLocation", checkpointPath) ...
<br />
<br />
<br />
