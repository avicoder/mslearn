---
    layout: post
    title: Troubleshoot inbound network connectivity for Azure Load Balancer - Diagnose issues by reviewing configurations and metrics
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/troubleshoot-inbound-connectivity-azure-load-balancer/3-diagnose-issues-by-reviewing-configurations-and-metrics/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/troubleshoot-inbound-connectivity-azure-load-balancer.svg">
####  1. What does the average Health Probe Status metric indicate?


<i class='far fa-square'></i> &nbsp;&nbsp;The number of virtual machines in the back-end pool that are responding to health probe requests.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The percentage of virtual machines in the back-end pool that are responding to health probe requests.

<i class='far fa-square'></i> &nbsp;&nbsp;The number of virtual machines available that will respond to client requests.
<br />
<br />
<br />

####  2. You're monitoring the average packet count metric for a load balancer. The average packet count suddenly increases by a significant amount, although the number of clients doesn't appear to have changed. What is the most probable cause?


<i class='far fa-square'></i> &nbsp;&nbsp;Additional virtual machines have become available in the back-end pool.

<i class='far fa-square'></i> &nbsp;&nbsp;The load balancing rule has stopped directing traffic to one or more virtual machines in the back-end pool.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;One or more virtual machines in the back-end pool are no longer responding to health probe requests and are no longer participating in load balancing.
<br />
<br />
<br />
