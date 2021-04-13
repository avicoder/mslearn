---
    layout: post
    title: Distributed computing on the cloud- MapReduce - Example MapReduce programs
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-analytics-engines-mapreduce/3-examples/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/distributed-programming-mapreduce.svg">
####  1. For the WordCount example, which combiner can be used to get the correct output?


<i class='far fa-square'></i> &nbsp;&nbsp;We can define a combiner function to return the MAX of the key-value pairs to get the same output.

<i class='far fa-square'></i> &nbsp;&nbsp;We can't use a combiner function in the WordCount example.

<i class='far fa-square'></i> &nbsp;&nbsp;We can define a combiner function to return the MIN of the key-value pairs to get the same output.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;We can use a reduce function as a combiner to get the same output
<br />
<br />
<br />
