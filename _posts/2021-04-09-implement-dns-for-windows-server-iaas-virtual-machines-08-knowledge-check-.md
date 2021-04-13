---
    layout: post
    title: Implement DNS for Windows Server IaaS VMs 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/implement-dns-for-windows-server-iaas-virtual-machines/08-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/implement-dns-for-windows-server-iaas-vm.svg">
####  1. Contoso IT staff want to ensure that internal and external clients resolve names to internal and external IP addresses respectively. What do they need to do?


<i class='far fa-square'></i> &nbsp;&nbsp;Set up split-horizon DNS by creating two DNS zones in Azure—one private and one public. The zones must have different names.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set up split-horizon DNS by creating two DNS zones in Azure—one private and one public, both with the same name.

<i class='far fa-square'></i> &nbsp;&nbsp;Set up split-horizon DNS by creating a single, private DNS zone in Azure.
<br />
<br />
<br />

####  2. After creating a private zone in Azure DNS, what must an administrator do before their resources can use the zone?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Link their VNets to the zone.

<i class='far fa-square'></i> &nbsp;&nbsp;Link their VMs to the zone.

<i class='far fa-square'></i> &nbsp;&nbsp;Enable autoregistration on the VNet link to the zone.
<br />
<br />
<br />

####  3. From an internet-connected on-premises host, Pavel is unable to resolve an IP address from an FQDN for one of the internet-facing VMs in Azure. He created a private DNS zone. What does he need to do?


<i class='far fa-square'></i> &nbsp;&nbsp;Troubleshoot DNS on the client by using a standard name resolution troubleshooting procedure. For example, empty the name cache, and then use nslookup to verify the resolution process.

<i class='far fa-square'></i> &nbsp;&nbsp;Make sure that the appropriate IP address is added as a record set in the DNS zone.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a public DNS zone for the domain name that contains the record, and add the record set for the VM's FQDN.
<br />
<br />
<br />
