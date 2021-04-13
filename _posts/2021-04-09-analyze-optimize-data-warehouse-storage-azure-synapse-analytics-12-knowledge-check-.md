---
    layout: post
    title: Analyze and optimize data warehouse storage in Azure Synapse Analytics 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/analyze-optimize-data-warehouse-storage-azure-synapse-analytics/12-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-synaps-analytics-optimize-data-warehouse.svg">
####  1. What would be the best approach to investigate if the data at hand is unevenly allocated across all distributions?


<i class='far fa-square'></i> &nbsp;&nbsp;Grouping the data based on partitions and counting rows with a T-SQL query.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Using DBCC PDW_SHOWSPACEUSED to see the number of table rows that are stored in each of the 60 distributions.

<i class='far fa-square'></i> &nbsp;&nbsp;Monitor query speeds by testing the same query for each partition.
<br />
<br />
<br />

####  2. To achieve improved query performance, which one would be the best data type for storing data that contains less than 128 characters?


<i class='far fa-square'></i> &nbsp;&nbsp;VARCHAR(MAX)

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;VARCHAR(128)

<i class='far fa-square'></i> &nbsp;&nbsp;NVARCHAR(128)
<br />
<br />
<br />

####  3. Which of the following statements is a benefit of materialized views?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Reducing the execution time for complex queries with JOINs and aggregate functions.

<i class='far fa-square'></i> &nbsp;&nbsp;Increased resiliency benefits.

<i class='far fa-square'></i> &nbsp;&nbsp;Increased high availability.
<br />
<br />
<br />
