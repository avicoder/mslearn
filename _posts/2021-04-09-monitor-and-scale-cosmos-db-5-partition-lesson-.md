---
    layout: post
    title: Optimize the performance of Azure Cosmos DB by using partitioning and indexing strategies - Identify a partition strategy for your Azure Cosmos DB data
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/monitor-and-scale-cosmos-db/5-partition-lesson/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/monitor-azure-cosmos-db.svg">
####  1. What causes a hot partition in a distributed NoSQL database collection?


<i class='far fa-square'></i> &nbsp;&nbsp;A partition key with a large number of values.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A partition key that doesn't distribute requests evenly over storage and time.

<i class='far fa-square'></i> &nbsp;&nbsp;A read-heavy workload.

<i class='far fa-square'></i> &nbsp;&nbsp;Querying a large volume of data.
<br />
<br />
<br />

####  2. What's the best way to maximize the efficiency of an individual database query?


<i class='far fa-square'></i> &nbsp;&nbsp;Minimize the number of queries to the database.

<i class='far fa-square'></i> &nbsp;&nbsp;Spread your write workload across partitions.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Design a partition key strategy so that your most frequent queries don't cross partitions.
<br />
<br />
<br />
