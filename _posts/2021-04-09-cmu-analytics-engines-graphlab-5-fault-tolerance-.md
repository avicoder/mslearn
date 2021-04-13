---
    layout: post
    title: Distributed computing on the cloud- GraphLab - Fault tolerance
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-analytics-engines-graphlab/5-fault-tolerance/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/distributed-programming-graphlab.svg">
####  1. What are the distributed checkpointing mechanisms that are used in GraphLab?


<i class='far fa-square'></i> &nbsp;&nbsp;Asynchronous

<i class='far fa-square'></i> &nbsp;&nbsp;Asynchronous and peer-to-peer

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Synchronous and asynchronous

<i class='far fa-square'></i> &nbsp;&nbsp;Synchronous

<i class='far fa-square'></i> &nbsp;&nbsp;Synchronous and master-subordinate
<br />
<br />
<br />

####  2. What's the main difference between synchronous and asynchronous mechanisms for checkpointing in GraphLab?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Synchronous checkpoints suspend the computation and flush all internal communication messages to capture the local checkpoint at every node. Asynchronous checkpoints can be run in parallel on vertices following edge consistency.

<i class='far fa-square'></i> &nbsp;&nbsp;Synchronous checkpoints halt the computation and flush all internal communication messages to capture the global checkpoint of the cluster. Asynchronous checkpoints can be run in parallel on vertices following vertex consistency.

<i class='far fa-square'></i> &nbsp;&nbsp;Synchronous checkpoints can be run in parallel on vertices following vertex consistency. Asynchronous checkpoints halt the computation and flush all internal communication messages to capture the global checkpoint of the cluster.
<br />
<br />
<br />
