---
    layout: post
    title: Distributed computing on the cloud- MapReduce - Computation and architectural models
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-analytics-engines-mapreduce/4-computation-architecture-model/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/distributed-programming-mapreduce.svg">
####  1. Based on Hadoop's architectural model, how are tasks assigned to slots in TaskTrackers?


<i class='far fa-square'></i> &nbsp;&nbsp;Push strategy: the JobTracker directly assigns tasks to individual task slots.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Pull strategy: the TaskTrackers notify the JobTracker of vacant slots and ask for tasks to be allotted to their vacant slots.

<i class='far fa-square'></i> &nbsp;&nbsp;Push-pull strategy: the JobTracker pushes tasks to TaskTrackers without checking for vacant slots, and TaskTrackers pull tasks from the JobTracker by always requesting them.
<br />
<br />
<br />
