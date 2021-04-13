---
    layout: post
    title: Case studies- NoSQL databases and cloud object storage - Apache HBase
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-case-study-nosql-databases/1-apache-hbase/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/case-studies-nosql-databases.svg">
####  1. How does Apache HBase tolerate region server failures?


<i class='far fa-square'></i> &nbsp;&nbsp;HBase always replicates each row when inserted to multiple region servers to provide redundancy.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;HBase commit logs are written to HDFS, which replicates it across multiple machines.

<i class='far fa-square'></i> &nbsp;&nbsp;The master always stores a copy of the data.

<i class='far fa-square'></i> &nbsp;&nbsp;HBase always replicates each row when inserted to multiple region servers to provide redundancy. HBase commit logs are written to HDFS, which replicates it across multiple machines.

<i class='far fa-square'></i> &nbsp;&nbsp;All of the above
<br />
<br />
<br />

####  2. An operation on an HBase table modifies 10 rows in sequence to zero out one of the columns. The column previously held the value of 1. Simultaneously, another HBase query retrieves the sum of that column over the same 10 rows through a Scan operation. What will be the result of the scan?


<i class='far fa-square'></i> &nbsp;&nbsp;5

<i class='far fa-square'></i> &nbsp;&nbsp;10

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Anywhere between 0 and 10

<i class='far fa-square'></i> &nbsp;&nbsp;0
<br />
<br />
<br />
