---
    layout: post
    title: Introduction to implementing lambda architecture for IoT solutions - Summary
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/introduction-lambda-architecture-iot-solutions/6-summary/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/iot/introduction-lambda-architecture-iot-solutions.svg">
####  1. What construct does Data Lake Gen 2 storage add to enhance data organization?


<i class='far fa-square'></i> &nbsp;&nbsp;Hot and cold paths

<i class='far fa-square'></i> &nbsp;&nbsp;Time Series Insights

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Hierarchical namespaces

<i class='far fa-square'></i> &nbsp;&nbsp;Failover regions
<br />
<br />
<br />

####  2. Which consistency level supports data writes being available immediately in the write-region, but data updates arriving in order, with varying latency, in the read-regions?


<i class='far fa-square'></i> &nbsp;&nbsp;Eventual consistency

<i class='far fa-square'></i> &nbsp;&nbsp;Strong consistency

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Session consistency

<i class='far fa-square'></i> &nbsp;&nbsp;Bounded consistency
<br />
<br />
<br />

####  3. What are the three visualizations available in Time Series Insights?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Charts, Heat maps, Tables

<i class='far fa-square'></i> &nbsp;&nbsp;Line charts, Heat maps, Graphs

<i class='far fa-square'></i> &nbsp;&nbsp;Hot maps, Cold maps, Tables

<i class='far fa-square'></i> &nbsp;&nbsp;Charts, Heat maps, Telemetry
<br />
<br />
<br />

####  4. What is the difference between a failover region, and a secondary read region?


<i class='far fa-square'></i> &nbsp;&nbsp;Nothing, they are the same.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A failover region takes over primary control, when the primary region fails. A secondary read region receives data updates from the primary region, but can't write data.

<i class='far fa-square'></i> &nbsp;&nbsp;A failover region takes over primary control, when the primary region fails. A secondary read region reads and writes data.

<i class='far fa-square'></i> &nbsp;&nbsp;A failover region is bypassed if a disaster occurs in the primary region. A secondary read region receives data updates from the primary region, but can't write data.
<br />
<br />
<br />
