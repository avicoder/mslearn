---
    layout: post
    title: Protect your on-premises infrastructure from disasters with Azure Site Recovery - Failover and failback
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/protect-on-premises-infrastructure-with-azure-site-recovery/5-failover-failback/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/protect-on-premises-infrastructure-with-azure-site-recovery.svg">
####  1. What is meant by the terms failover and failback in the context of disaster recovery?


<i class='far fa-square'></i> &nbsp;&nbsp;Failover is the transfer of workload from the secondary site to a primary site during a test or disaster recovery scenario. Failback is when the workload gets transferred back to the secondary site.

<i class='far fa-square'></i> &nbsp;&nbsp;Failover is the time taken between discovering there has been a disaster and invoking actual disaster recovery. Failback is the time taken between fixing the disaster and when the environment is running from the primary site again.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Failover is the transfer of workload to a secondary site during a test or disaster scenario. Failback is when the workload gets transferred back over to the primary site from the secondary site.
<br />
<br />
<br />

####  2. What is the correct order for the four stages of failover and failback when you replicate your on-premises environment to Azure?


<i class='far fa-square'></i> &nbsp;&nbsp;Reprotect Azure virtual machines by replicating back to on-premises. Fail over to the secondary site on Azure. Fail back to the primary on-premises site. Reprotect the on-premises virtual machines by replicating to Azure.

<i class='far fa-square'></i> &nbsp;&nbsp;Fail back to the primary on-premises site. Reprotect the on-premises virtual machines by replicating to Azure. Fail over to the secondary site on Azure. Reprotect the Azure virtual machines by replicating back to on-premises.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Fail over to the secondary site on Azure. Reprotect the Azure virtual machines by replicating back to on-premises. Fail back to the primary on-premises site. Reprotect the on-premises virtual machines by replicating to Azure.
<br />
<br />
<br />
