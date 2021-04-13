---
    layout: post
    title: Implement hybrid backup and recovery with Windows Server IaaS 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/implement-hybrid-backup-recovery-windows-server-iaas/9-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/implement-hybrid-backup-and-recovery-with-windows-server-iaas.svg">
####  1. Larissa is responsible for implementing server workload backups at Contoso. She wants to implement on-premises backups to an Azure Recovery Vault service. What does Larissa need to do on the Windows Servers she wants to back up?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Larissa must download and install the MARS agent, and then register the server by installing the vault credentials.

<i class='far fa-square'></i> &nbsp;&nbsp;Larissa must download and install the MARS agent.

<i class='far fa-square'></i> &nbsp;&nbsp;Larissa doesn't need to do anything. Windows Servers contain the required agent for inclusion in the Recovery Vault service.
<br />
<br />
<br />

####  2. After creating Contoso's Recovery Vault service, Larissa discovers that she wants to change the storage replication type to locally redundant. In which situations can Larissa change the storage replication type?


<i class='far fa-square'></i> &nbsp;&nbsp;Larissa can change this setting at any time.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Larissa can change this setting, but only before a Recovery Vault service starts providing protection for items.

<i class='far fa-square'></i> &nbsp;&nbsp;Larissa cannot change this setting at any time.
<br />
<br />
<br />

####  3. Larissa has been archiving and tidying unneeded backup data. She has just removed some backup data from Azure Backup. She's just been informed that this removed data is required to restore some damaged files. What are Larissa's options?


<i class='far fa-square'></i> &nbsp;&nbsp;Larissa can do nothing about it. The backup data is unrecoverable.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Larissa can recover the removed backup data for up to 14 days after deletion.

<i class='far fa-square'></i> &nbsp;&nbsp;Larissa can recover the removed backup data for up to 21 days after deletion.
<br />
<br />
<br />
