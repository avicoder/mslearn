---
    layout: post
    title: What is distributed programming? - Programming models for clouds
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-distributed-programming-introduction/4-program-cloud-models/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/distributed-programming-introduction.svg">
####  1. A password-recovery program for ZIP archives works by brute-force trial of the entire password keyspace. The program has a parallel mode, which is used on a single computer but requires a multicore processor. What kind of parallelization technique is this program most likely to utilize?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Shared memory

<i class='far fa-square'></i> &nbsp;&nbsp;Message passing
<br />
<br />
<br />

####  2. A more advanced password-recovery program allows the user to set up a computational cluster using multiple machines to further speed up the brute-force search. The machines in the cluster should be connected using some kind of network but do not implement any kind of distributed shared memory (DSM). What kind of parallelization technique is this program most likely to utilize?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Message passing

<i class='far fa-square'></i> &nbsp;&nbsp;Shared memory
<br />
<br />
<br />

####  3. What is the main difference between message-passing and shared-memory models?


<i class='far fa-square'></i> &nbsp;&nbsp;Message passing requires explicit messages to be sent between nodes, while the shared-memory model assumes the existence of a shared address space through which all parallel processes of the application can access data.

<i class='far fa-square'></i> &nbsp;&nbsp;Shared memory requires explicit messages to be sent through a shared address space, while processes in message passing use a network to synchronize execution.

<i class='far fa-square'></i> &nbsp;&nbsp;Shared-memory models require explicit synchronization, while message-passing models do not.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Message passing requires explicit messages to be sent between nodes, while the shared-memory model assumes the existence of a shared address space through which all parallel processes of the application can access data. Shared-memory models require explicit synchronization, while message-passing models do not.

<i class='far fa-square'></i> &nbsp;&nbsp;Shared memory requires explicit messages to be sent through a shared address space, while processes in message passing use a network to synchronize execution. Shared-memory models require explicit synchronization, while message-passing models do not.
<br />
<br />
<br />
