---
    layout: post
    title: Introduction to Azure hybrid cloud services - Hybrid identity
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/intro-to-azure-hybrid-services/4-hybrid-identity/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/intro-to-azure-hybrid-services.svg">
####  1. Among the virtual machines that Tailwind Traders is planning to migrate out of the Auckland datacenter, several host applications have dependencies on AD DS that include custom schema extensions and custom AD DS partitions. Which of the following hybrid-identity solutions can the company use to support these applications if the virtual machines that host the applications are migrated to run as Azure infrastructure as a service (IaaS) VMs?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure Azure AD Connect to replicate the on-premises AD DS identities to Azure. Create a subnet in an Azure virtual network. Migrate the VMs from the Auckland datacenter to this subnet. Join the migrated VMs to the Azure AD domain.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a subnet in an Azure virtual network. Configure a VPN connection between this virtual network and the on-premises network. Deploy two AD DS domain controllers on VMs running Windows Server 2019 on this subnet. Configure a separate AD DS site for the Azure subnet. Migrate the VMs from the Auckland datacenter to this subnet.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure Azure AD Connect to replicate the on-premises AD DS identities to Azure. Create a subnet in an Azure virtual network. Configure Azure AD DS and configure it to be available to this newly created subnet. Migrate the VMs from the Auckland datacenter to this subnet. Join the migrated VMs to the Azure AD domain.
<br />
<br />
<br />

####  2. A Tailwind Traders subsidiary is deploying Windows Server 2019 IaaS VMs onto a subnet in an Azure virtual network. This virtual network is connected to a separate subscription and Azure AD tenancy. These computers need to be domain joined for security and identity purposes, but they don't require complex group policy configuration. These VMs don't require identities synchronized from any on-premises Tailwind Traders AD DS instance. You want to minimize the number of VMs that you deploy to achieve this goal. Which of the following solutions is appropriate?


<i class='far fa-square'></i> &nbsp;&nbsp;Deploy Azure AD Connect on each VM and synchronize with the Azure AD tenancy.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Deploy Azure AD DS and configure it for the subnet that hosts the virtual machines. Join the VMs to the Azure AD DS domain.

<i class='far fa-square'></i> &nbsp;&nbsp;Deploy AD DS on a new VM on the subnet. Join the VMs to the AD DS domain.
<br />
<br />
<br />
