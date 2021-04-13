---
    layout: post
    title: Insert and query data in your Azure Cosmos DB database - Explore SQL query types
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/access-data-with-cosmos-db-and-sql-api/4-query-types/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/access-data-with-cosmos-db-and-sql-api.svg">
####  1. What is the only required clause in a SQL query?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;SELECT

<i class='far fa-square'></i> &nbsp;&nbsp;FROM

<i class='far fa-square'></i> &nbsp;&nbsp;WHERE
<br />
<br />
<br />

####  2. Which query will get an ordered list of product IDs and descriptions, starting with the largest product ID and ending with the smallest product ID?


<i class='far fa-square'></i> &nbsp;&nbsp;SELECT p.productId FROM Products p ORDER BY p.productId ASC

<i class='far fa-square'></i> &nbsp;&nbsp;SELECT p.id FROM Products p ORDER BY p.productId DESC

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;SELECT p.productId, p.description FROM Products p ORDER BY p.productId DESC
<br />
<br />
<br />
