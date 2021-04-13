---
    layout: post
    title: Design a multidimensional schema to optimize analytical workloads 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/design-multidimensional-schema-to-optimize-analytical-workloads/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-synapse-analytics-multi-dimensional-schema.svg">
####  1. What distribution option would you use for a product dimension table that will contain 1,000 records in Synapse Analytics?


<i class='far fa-square'></i> &nbsp;&nbsp;DISTRIBUTION = ROUND_ROBIN.

<i class='far fa-square'></i> &nbsp;&nbsp;DISTRIBUTION = HASH([ProductId]).

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;DISTRIBUTION = REPLICATE.
<br />
<br />
<br />

####  2. What distribution option would be best for a sales fact table that will contain billions of records?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;DISTRIBUTION = HASH([SalesOrderNumber]).

<i class='far fa-square'></i> &nbsp;&nbsp;DISTRIBUTION = HEAP.

<i class='far fa-square'></i> &nbsp;&nbsp;DISTRIBUTION = REPLICATE.
<br />
<br />
<br />

####  3. What is the difference between a star schema and a snowflake schema?


<i class='far fa-square'></i> &nbsp;&nbsp;A star schema uses surrogate keys while a snowflake schema uses business keys.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;All dimensions in a star schema join directly to the fact table (denormalized) while some dimension tables in a snowflake schema are normalized.

<i class='far fa-square'></i> &nbsp;&nbsp;All dimensions in a star schema are normalized while all dimensions in a snowflake schema join directly to the fact table (denormalized).

<i class='far fa-square'></i> &nbsp;&nbsp;A star schema has one fact table while a snowflake schema has multiple fact tables.
<br />
<br />
<br />
