---
    layout: post
    title: Design your site recovery solution in Azure - Develop a business continuity and disaster recovery plan
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/design-your-site-recovery-solution-in-azure/2-develop-bcdr-plan/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/design-your-site-recovery-solution-on-azure.svg">
####  1. List the differences between Azure Backup and Azure Site Recovery, and identify a scenario where Azure Backup or Azure Site Recovery should be used.


<i class='far fa-square'></i> &nbsp;&nbsp;Azure Site Recovery can be used to protect Azure VMs, Azure Backup is only used to protect on-premises targets. You would use Azure Site Recovery to trigger a failover from on-premises virtual machines to an Azure environment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Azure Site Recovery can be used to keep your workloads running, Azure Backup is used for keeping your data safe.

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Site Recovery can be used for retaining long-term data, Azure Backup is only used for short-term data retention. You would use Azure Backup to trigger a test failover on from on-premises infrastructure to an Azure infrastructure.
<br />
<br />
<br />

####  2. What are some Azure features that contribute to high availability of virtual machines?


<i class='far fa-square'></i> &nbsp;&nbsp;Availability Sets, Recovery Zones.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Availability Zones, Region pairing.

<i class='far fa-square'></i> &nbsp;&nbsp;Availability Points, Region Pairing.
<br />
<br />
<br />
