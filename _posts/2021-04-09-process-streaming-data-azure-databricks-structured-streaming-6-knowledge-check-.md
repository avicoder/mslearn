---
    layout: post
    title: Process streaming data with Azure Databricks structured streaming 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/process-streaming-data-azure-databricks-structured-streaming/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/process-streaming-data-azure-databricks-structured-streaming.svg">
####  1. When doing a write stream command, what does the outputMode("append") option do?


<i class='far fa-square'></i> &nbsp;&nbsp;The append mode allows records to be updated and changed in place

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The append outputMode allows records to be added to the output sink

<i class='far fa-square'></i> &nbsp;&nbsp;The append mode replaces existing records and updates aggregates
<br />
<br />
<br />

####  2. In Spark Structured Streaming, what method should be used to read streaming data into a DataFrame?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;spark.readStream

<i class='far fa-square'></i> &nbsp;&nbsp;spark.read

<i class='far fa-square'></i> &nbsp;&nbsp;spark.stream.read
<br />
<br />
<br />

####  3. What happens if the command option("checkpointLocation", pointer-to-checkpoint directory) is not specified?


<i class='far fa-square'></i> &nbsp;&nbsp;It will not be possible to create more than one streaming query that uses the same streaming source since they will conflict

<i class='far fa-square'></i> &nbsp;&nbsp;The streaming job will function as expected since the checkpointLocation option does not exist

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When the streaming job stops, all state around the streaming job is lost, and upon restart, the job must start from scratch
<br />
<br />
<br />
