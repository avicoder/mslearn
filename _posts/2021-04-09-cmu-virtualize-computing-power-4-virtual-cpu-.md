---
    layout: post
    title: Virtualize computing power - Use virtual CPUs
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-virtualize-computing-power/4-virtual-cpu/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/virtualize-computing-power.svg">
####  1. What is a virtual machine with a width of 12 called?


<i class='far fa-square'></i> &nbsp;&nbsp;A uniprocessor virtual machine

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A symmetric multiprocessor virtual machine
<br />
<br />
<br />

####  2. At different points in time, a vCPU can run at different pCPUs.


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;True

<i class='far fa-square'></i> &nbsp;&nbsp;False
<br />
<br />
<br />

####  3. Assume an SEDF scheduler has the following three vCPUs:vCPU1: slice = 20 ms and period = 100 msvCPU2: slice = 2 ms and period = 10 msvCPU3: slice = 5 ms and period = 10 msAssume all of the vCPUs are in the ready state. Which of the three vCPUs will be selected next by SEDF?


<i class='far fa-square'></i> &nbsp;&nbsp;vCPU1

<i class='far fa-square'></i> &nbsp;&nbsp;vCPU2

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;vCPU3
<br />
<br />
<br />

####  4. Assume a machine with one pCPU and a credit scheduler has the following two vCPUs:vCPU1: weight = 128 and cap = 25%vCPU2: weight = 256 and no capWhich of the following statements is correct?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;vCPU2 will get twice as much pCPU time as vCPU1 until vCPU1 reaches its cap of 25\%.

<i class='far fa-square'></i> &nbsp;&nbsp;vCPU1 will get a quarter as much pCPU time as vCPU2 until it reaches its cap of 25\%.

<i class='far fa-square'></i> &nbsp;&nbsp;vCPU1 will get half as much pCPU time as vCPU2 all the time and for 100\% of the pCPU capacity.

<i class='far fa-square'></i> &nbsp;&nbsp;vCPU1 will get half as much pCPU time as vCPU2 until vCPU2 reaches a cap of 75\%.

<i class='far fa-square'></i> &nbsp;&nbsp;vCPU1 will get half as much pCPU time as vCPU2 until vCPU2 reaches a cap of 25\%.
<br />
<br />
<br />
