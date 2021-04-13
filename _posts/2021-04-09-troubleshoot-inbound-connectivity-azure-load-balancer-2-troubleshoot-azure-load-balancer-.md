---
    layout: post
    title: Troubleshoot inbound network connectivity for Azure Load Balancer - Troubleshoot Azure Load Balancer
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/troubleshoot-inbound-connectivity-azure-load-balancer/2-troubleshoot-azure-load-balancer/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/troubleshoot-inbound-connectivity-azure-load-balancer.svg">
####  1. What happens if a health probe isn't configured and a VM fails?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Azure Load Balancer won't notice the failure and continues to route traffic to the failed VM. This issue causes requests to time out.

<i class='far fa-square'></i> &nbsp;&nbsp;Load Balancer removes the VM from the back-end pool.

<i class='far fa-square'></i> &nbsp;&nbsp;Load Balancer doesn't know which VM has failed and so stops sending requests to all VMs in the back-end pool.
<br />
<br />
<br />

####  2. You closed a port in a network security group used by a virtual network that hosts the VMs in the Load Balancer pool. How might this affect load balancing?


<i class='far fa-square'></i> &nbsp;&nbsp;If one is available, Load Balancer attempts to use a different port. Requests are sent to VMs through this port instead.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;If the port is used to send traffic to the VMs in the pool, then this traffic is blocked. All requests time out and eventually fail. If this port was a probe port, the VM is removed from rotation.

<i class='far fa-square'></i> &nbsp;&nbsp;Load Balancer queues client requests until the port is opened again. At that point, the requests are sent.
<br />
<br />
<br />
