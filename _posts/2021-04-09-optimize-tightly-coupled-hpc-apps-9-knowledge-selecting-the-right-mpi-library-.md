---
    layout: post
    title: Optimizing tightly coupled HPC applications on HBv2, HC, and HB series virtual machines  - Select the right MPI library
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/optimize-tightly-coupled-hpc-apps/9-knowledge-selecting-the-right-mpi-library/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/generic-badge.svg">
####  1. Which MPI libraries will work on the HB120_v2, HB60, and HC44 VMs?


<i class='far fa-square'></i> &nbsp;&nbsp;Only Intel MPI, because Azure only supports the DAPL InfiniBand API

<i class='far fa-square'></i> &nbsp;&nbsp;Mellanox tuned HPCX MPI library

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;All popular MPI libraries
<br />
<br />
<br />

####  2. Which MPI library is recommended on HB120, HB60, and HC44?


<i class='far fa-square'></i> &nbsp;&nbsp;Intel MPI 2019 update5+

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;HPCX MPI library

<i class='far fa-square'></i> &nbsp;&nbsp;Any MPI library on the CentOS-HPC 7.8+ Azure Marketplace image, because they all have the same performance
<br />
<br />
<br />

####  3. Which MPI library is ABI compatible with mpich library?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Intel MPI

<i class='far fa-square'></i> &nbsp;&nbsp;HPCX MPI library

<i class='far fa-square'></i> &nbsp;&nbsp;All MPI libraries are ABI compatible
<br />
<br />
<br />
