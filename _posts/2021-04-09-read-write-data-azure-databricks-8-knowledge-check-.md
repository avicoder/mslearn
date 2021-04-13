---
    layout: post
    title: Read and write data in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/read-write-data-azure-databricks/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/read-write-data-azure-databricks.svg">
####  1. How do you list files in DBFS within a notebook?


<i class='far fa-square'></i> &nbsp;&nbsp;ls /my-file-path

<i class='far fa-square'></i> &nbsp;&nbsp;\%fs dir /my-file-path

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;\%fs ls /my-file-path
<br />
<br />
<br />

####  2. How do you infer the data types and column names when you read a JSON file?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;spark.read.option("inferSchema", "true").json(jsonFile)

<i class='far fa-square'></i> &nbsp;&nbsp;spark.read.inferSchema("true").json(jsonFile)

<i class='far fa-square'></i> &nbsp;&nbsp;spark.read.option("inferData", "true").json(jsonFile)
<br />
<br />
<br />
