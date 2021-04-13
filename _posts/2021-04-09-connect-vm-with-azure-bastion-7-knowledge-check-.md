---
    layout: post
    title: Connect to virtual machines through the Azure portal by using Azure Bastion 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/connect-vm-with-azure-bastion/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/connect-vm-with-azure-bastion.svg">
####  1. An organization has set up virtual machines (VMs) to act as jumpboxes in each of its six virtual networks. Why should the organization consider using Azure Bastion?


<i class='far fa-square'></i> &nbsp;&nbsp;The organization can eliminate the need to manage its virtual networks.

<i class='far fa-square'></i> &nbsp;&nbsp;The organization can eliminate all of its VM management work.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The organization can simplify the management of its VMs.
<br />
<br />
<br />

####  2. At what resource level or scope does an Azure Bastion connection apply to?


<i class='far fa-square'></i> &nbsp;&nbsp;Resource group

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Virtual network or peered virtual networks

<i class='far fa-square'></i> &nbsp;&nbsp;Subscription
<br />
<br />
<br />

####  3. You decide to deploy Azure Bastion to an existing virtual network by using the Azure CLI. What resources do you need to create?


<i class='far fa-square'></i> &nbsp;&nbsp;VM, public IP, and Azure Bastion

<i class='far fa-square'></i> &nbsp;&nbsp;Subnet named AzureBastionSubnet and at least one VM

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Subnet named AzureBastionSubnet, public IP, and Azure Bastion
<br />
<br />
<br />

####  4. Several of your peers are having trouble connecting to VMs by using Azure Bastion. What isn't likely to cause the problem?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The public IP address of the destination VM

<i class='far fa-square'></i> &nbsp;&nbsp;The number of current remote connections

<i class='far fa-square'></i> &nbsp;&nbsp;Network security group rules
<br />
<br />
<br />

####  5. You want to add an extra layer of security to Azure Bastion. Where can you start?


<i class='far fa-square'></i> &nbsp;&nbsp;Deny all inbound TCP network traffic to the Azure Bastion public IP

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Apply role-based access control (RBAC) and the least privilege to use and manage Azure Bastion

<i class='far fa-square'></i> &nbsp;&nbsp;Remove the reader role on the Azure Bastion resource for all users
<br />
<br />
<br />
