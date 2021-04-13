---
    layout: post
    title: Introduction to Hyperscale (Citus) on Azure Database for PostgreSQL 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/intro-to-hyperscale/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/intro-to-hyperscale.svg">
####  1. What are the characteristics of OLTP workloads?


<i class='far fa-square'></i> &nbsp;&nbsp;High numbers of transactions with large amounts of data

<i class='far fa-square'></i> &nbsp;&nbsp;Business intelligence and analytical workloads

<i class='far fa-square'></i> &nbsp;&nbsp;Time series data

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;High numbers of transactions with low amounts of data
<br />
<br />
<br />

####  2. Why do multi-tenant applications provide massive cost savings?


<i class='far fa-square'></i> &nbsp;&nbsp;OLAP workloads involve low amounts of data

<i class='far fa-square'></i> &nbsp;&nbsp;The combined workloads of multiple tenants is low

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Many customers share resources.

<i class='far fa-square'></i> &nbsp;&nbsp;Recent cloud advances in storing large amounts of data.
<br />
<br />
<br />

####  3. What is a benefit of sharding?


<i class='far fa-square'></i> &nbsp;&nbsp;OLAP workloads only need to access a single node to run queries

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Sharding allows efficient distribution of your data to multiple servers, allowing a level of performance that is impossible to achieve on a single server.

<i class='far fa-square'></i> &nbsp;&nbsp;Queries can be combined into a single, master query.

<i class='far fa-square'></i> &nbsp;&nbsp;Sharding allows applications to directly query worker nodes, removing the need for a coordinator node.
<br />
<br />
<br />
