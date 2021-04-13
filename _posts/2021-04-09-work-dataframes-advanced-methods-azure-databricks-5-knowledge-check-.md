---
    layout: post
    title: Work with DataFrames advanced methods in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-dataframes-advanced-methods-azure-databricks/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-dataframes-advanced-methods-azure-databricks.svg">
####  1. Which method for renaming a DataFrame's column is incorrect?


<i class='far fa-square'></i> &nbsp;&nbsp;df.select(col("timestamp").alias("dateCaptured"))

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;df.alias("timestamp", "dateCaptured")

<i class='far fa-square'></i> &nbsp;&nbsp;df.toDF("dateCaptured")
<br />
<br />
<br />

####  2. You need to find the average of sales transactions by storefront. Which of the following aggregates would you use?


<i class='far fa-square'></i> &nbsp;&nbsp;df.select(col("storefront")).avg("completedTransactions")

<i class='far fa-square'></i> &nbsp;&nbsp;df.groupBy(col("storefront")).avg(col("completedTransactions"))

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;df.groupBy(col("storefront")).avg("completedTransactions")
<br />
<br />
<br />
