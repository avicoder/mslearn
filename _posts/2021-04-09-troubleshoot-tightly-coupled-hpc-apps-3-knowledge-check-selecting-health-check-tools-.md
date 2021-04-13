---
    layout: post
    title: Troubleshoot tightly coupled HPC applications on HBv2, HC, and HB series virtual machines 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/troubleshoot-tightly-coupled-hpc-apps/3-knowledge-check-selecting-health-check-tools/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/generic-badge.svg">
####  1. The HPC application runs correctly on 64 HB120_v2. Should you still run some health checks?


<i class='far fa-square'></i> &nbsp;&nbsp;There's no need. The application is running correctly.

<i class='far fa-square'></i> &nbsp;&nbsp;I should run health checks only after every third deployment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes, I should still run some health checks.
<br />
<br />
<br />

####  2. What is the recommended tool to check the health of the InfiniBand interconnect?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Intel IMB-IMP1 PingPong built with HPC-X.

<i class='far fa-square'></i> &nbsp;&nbsp;Intel IMB-IMPI1 PingPong contained in the Intel MPI environment on a CentOS HPC 7.7+ Azure Marketplace image.

<i class='far fa-square'></i> &nbsp;&nbsp;HPL built with HPC-X.
<br />
<br />
<br />

####  3. What is the recommended tool to check the health of the VM's memory?


<i class='far fa-square'></i> &nbsp;&nbsp;IOR benchmark tool.

<i class='far fa-square'></i> &nbsp;&nbsp;Intel IMP-IMP1 PingPong.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Intel MLC.
<br />
<br />
<br />
