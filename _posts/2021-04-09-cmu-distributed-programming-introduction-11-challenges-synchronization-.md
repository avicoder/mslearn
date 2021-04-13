---
    layout: post
    title: What is distributed programming? - Cloud challenges- Synchronization
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-distributed-programming-introduction/11-challenges-synchronization/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/distributed-programming-introduction.svg">
####  1. Assume the following function:    Assume that initially accounts A and B both have 100 dollars and the following operations are executed simultaneously, such that both operations acquire a lock on the source account (as indicated in line number 3 in the transaction function) at the same time:    What will be the result?


<i class='far fa-square'></i> &nbsp;&nbsp;A will have 140 dollars and B will have 60 dollars.

<i class='far fa-square'></i> &nbsp;&nbsp;A will have 60 dollars and B will have 90 dollars.

<i class='far fa-square'></i> &nbsp;&nbsp;A will have 110 dollars and B will have 90 dollars.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The transactions will never finish due to a deadlock.
<br />
<br />
<br />
