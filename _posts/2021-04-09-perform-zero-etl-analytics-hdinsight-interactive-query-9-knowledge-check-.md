---
    layout: post
    title: Perform Zero ETL analytics with HDInsight Interactive Query 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/perform-zero-etl-analytics-hdinsight-interactive-query/9-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/perform-zero-etl-analytics-with-hdinsights-interactive-query.svg">
####  1. Which user requirements are best suited for using HDInsight Interactive Query?


<i class='far fa-square'></i> &nbsp;&nbsp;When you want to use MapReduce on unstructured data with role-based access controls.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When you want to use SQL-like queries on structured data with row and column level controls.

<i class='far fa-square'></i> &nbsp;&nbsp;When you want to use SQL-like queries on high concurrency data for long running-computations.
<br />
<br />
<br />

####  2. What file formats are supported with Interactive Query?


<i class='far fa-square'></i> &nbsp;&nbsp;.xml, .doc, .log

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;.json, .csv, .txt

<i class='far fa-square'></i> &nbsp;&nbsp;.pdf, .dbk, .md
<br />
<br />
<br />

####  3. Which scenario is best for HDInsight Interactive Query?


<i class='far fa-square'></i> &nbsp;&nbsp;Batch processing

<i class='far fa-square'></i> &nbsp;&nbsp;Streaming data

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Ad hoc queries
<br />
<br />
<br />

####  4. Why is the Hive Warehouse Connector needed?


<i class='far fa-square'></i> &nbsp;&nbsp;Hive and Spark are different cluster types.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Hive and Spark have two different metastores, they require a connector to bridge between the two.

<i class='far fa-square'></i> &nbsp;&nbsp;Hive is for static data and Spark is for streaming data.
<br />
<br />
<br />

####  5. Why is using the Hive Warehouse Connector more efficient and scalable than using a standard JDBC connection from Spark to Hive?


<i class='far fa-square'></i> &nbsp;&nbsp;Because the library loads data from the HiveServer into the spark driver in parallel

<i class='far fa-square'></i> &nbsp;&nbsp;Because the Hive Warehouse Connector is optimized for streaming data

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Because the library loads data from LLAP daemons into Spark executors in parallel
<br />
<br />
<br />
