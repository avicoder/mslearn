---
    layout: post
    title: Configure BitLocker disk encryption for Windows IaaS Virtual Machines 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/configure-bitlocker-disk-encryption-windows-iaas-virtual-machines/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/configure-bitlocker-disk-encryption-for-windows-iaas-vms.svg">
####  1. When you enable Azure Disk Encryption on a Windows VM, what technology does it use on the VM to encrypt the data on your VHDs?


<i class='far fa-square'></i> &nbsp;&nbsp;DM-Crypt.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;BitLocker.

<i class='far fa-square'></i> &nbsp;&nbsp;Key Vault.
<br />
<br />
<br />

####  2. To use Key Vault with Azure Disk Encryption, what policy must an administrator set?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure an access policy to permit at least one security principal.

<i class='far fa-square'></i> &nbsp;&nbsp;Create an access policy to allow template deployment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set the key vault access policy to support disk encryption.
<br />
<br />
<br />

####  3. Suppose an administrator creates a new VM with a single operating system disk and a single data disk. They use the default options when they create the VM. They don't have a key vault set up in their subscription. Which option most accurately describes the encryption state of those disks?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Both disks are encrypted using server-side encryption.

<i class='far fa-square'></i> &nbsp;&nbsp;Both disks are unencrypted.

<i class='far fa-square'></i> &nbsp;&nbsp;The operating system disk is encrypted using server-side encryption. The data disk is unencrypted.
<br />
<br />
<br />
