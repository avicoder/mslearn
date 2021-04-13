---
    layout: post
    title: Secure your Azure virtual machine disks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/secure-your-azure-virtual-machine-disks/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/secure-your-azure-virtual-machine-disks.svg">
####  1. When you enable Azure Disk Encryption (ADE) on a Windows virtual machine (VM), what does it use to encrypt the data on your virtual hard disks?


<i class='far fa-square'></i> &nbsp;&nbsp;DM-Crypt

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;BitLocker

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Key Vault
<br />
<br />
<br />

####  2. To use Azure Key Vault with ADE, what policy do you need to set?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure an access policy to permit at least one security principal.

<i class='far fa-square'></i> &nbsp;&nbsp;Create an access policy to allow template deployment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set the key vault access policy to support disk encryption.
<br />
<br />
<br />

####  3. Suppose you create a new VM with a single OS disk and a single data disk. You use the default options when you create the VM. You don't have an Azure Key Vault set up in your subscription. Which option most accurately describes the encryption state of those disks?


<i class='far fa-square'></i> &nbsp;&nbsp;Both disks are unencrypted.

<i class='far fa-square'></i> &nbsp;&nbsp;The OS disk is encrypted using Storage Service Encryption (SSE). The data disk is unencrypted.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Both disks are encrypted using Storage Service Encryption.
<br />
<br />
<br />
