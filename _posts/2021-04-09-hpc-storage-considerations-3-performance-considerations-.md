---
    layout: post
    title: Understand factors that influence HPC storage selection in Azure - File-system performance considerations
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/hpc-storage-considerations/3-performance-considerations/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/hpc-storage-considerations.svg">
####  1. Small block sizes will reduce performance if your files are:


<i class='far fa-square'></i> &nbsp;&nbsp;Small

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Large
<br />
<br />
<br />

####  2. If you have a disk that supports 5,000 IOPS and your block size is 4K, your total possible throughput is:


<i class='far fa-square'></i> &nbsp;&nbsp;9 MBps

<i class='far fa-square'></i> &nbsp;&nbsp;15 MBps

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;20 MBps
<br />
<br />
<br />
