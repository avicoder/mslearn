---
    layout: post
    title: Cloud storage overview - Relational databases
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-cloud-storage/10-relational-databases/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/cloud-storage-overview.svg">
####  1. A monolithic (single node) RDBMS server is used to deploy a database. Assuming that the database is always reachable and is ACID compliant, which of the CAP theorem constraints is satisfied by this server?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;CA

<i class='far fa-square'></i> &nbsp;&nbsp;AP

<i class='far fa-square'></i> &nbsp;&nbsp;CP
<br />
<br />
<br />

####  2. Given a system that uses sharding to distribute data among multiple nodes in an RDBMS cluster, which of the following queries will require distributed concurrency control (using 2PC or similar mechanisms) to execute safely?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A query that calculates an aggregate value across all rows of a table and writes that value across all the rows of a table

<i class='far fa-square'></i> &nbsp;&nbsp;A query that involves a single-row transaction
<br />
<br />
<br />
