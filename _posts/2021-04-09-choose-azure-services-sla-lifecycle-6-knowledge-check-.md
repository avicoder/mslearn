---
    layout: post
    title: Choose the right Azure services by examining SLAs and service lifecycle 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/choose-azure-services-sla-lifecycle/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/explore-azure-service-level-agreements.svg">
####  1. What's the SLA for Azure Maps in terms of guaranteed uptime?


<i class='far fa-square'></i> &nbsp;&nbsp;99 percent

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;99.9 percent

<i class='far fa-square'></i> &nbsp;&nbsp;99.99 percent
<br />
<br />
<br />

####  2. What's the new composite SLA? Remember, the new SLA includes a third virtual machine and Azure Maps.


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;99.58 percent

<i class='far fa-square'></i> &nbsp;&nbsp;99.78 percent

<i class='far fa-square'></i> &nbsp;&nbsp;99.99 percent
<br />
<br />
<br />

####  3. Adding a third virtual machine reduces the composite SLA. How can Tailwind Traders offset this reduction?


<i class='far fa-square'></i> &nbsp;&nbsp;Increase the size of each virtual machine.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Deploy extra instances of the same virtual machines across the different availability zones in the same Azure region.

<i class='far fa-square'></i> &nbsp;&nbsp;Do nothing. Using Azure Load Balancer increases the SLA for virtual machines.
<br />
<br />
<br />

####  4. What approach might the company take in adding the augmented reality (AR) preview service to its architecture?


<i class='far fa-square'></i> &nbsp;&nbsp;The Special Orders app is already in production. The company shouldn't look into the AR service until the service reaches general availability (GA).

<i class='far fa-square'></i> &nbsp;&nbsp;The Special Orders app is mainly for use by retail employees. The company can integrate the AR service now because potential downtime or failures aren't an important factor.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The development team can create a prototype version of the app that includes the AR service that it tests out with select retail employees.
<br />
<br />
<br />
