---
    layout: post
    title: Build and query a Delta Lake 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-query-delta-lake/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/build-query-delta-lake.svg">
####  1. What is the Databricks Delta command to display metadata?


<i class='far fa-square'></i> &nbsp;&nbsp;MSCK DETAIL tablename

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;DESCRIBE DETAIL tableName

<i class='far fa-square'></i> &nbsp;&nbsp;SHOW SCHEMA tablename
<br />
<br />
<br />

####  2. How do you perform UPSERT in a Delta dataset?


<i class='far fa-square'></i> &nbsp;&nbsp;Use UPSERT INTO my-table

<i class='far fa-square'></i> &nbsp;&nbsp;Use UPSERT INTO my-table /MERGE

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use MERGE INTO my-table USING data-to-upsert
<br />
<br />
<br />

####  3. What optimization does the following command perform: OPTIMIZE Students ZORDER BY Grade?


<i class='far fa-square'></i> &nbsp;&nbsp;Creates an order-based index on the Grade field to improve filters against that field

<i class='far fa-square'></i> &nbsp;&nbsp;Ensures that all data backing, for example, Grade=8 is colocated, then updates a graph that routes requests to the appropriate files

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Ensures that all data backing, for example, Grade=8 is colocated, then rewrites the sorted data into new Parquet files
<br />
<br />
<br />

####  4. What size does OPTIMIZE compact small files to?


<i class='far fa-square'></i> &nbsp;&nbsp;Around 100 MB

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Around 1 GB

<i class='far fa-square'></i> &nbsp;&nbsp;Around 500 MB
<br />
<br />
<br />
