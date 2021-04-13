---
    layout: post
    title: Network design principles for enterprise-scale architecture - Network topology for enterprise-scale
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/enterprise-scale-networking/4-network-topology/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/enterprise-scale-networking.svg">
####  1. Contoso is deploying a network solution in Azure. It needs to deploy a solution in a single Azure region, and it needs to connect about 500 branch offices via VPN, as well as one main office via ExpressRoute. Contoso will deploy about 500 VMs across 50 virtual networks. Azure Firewall must protect the following traffic: virtual network to virtual network, virtual network to internet, branch to virtual network, and main office to virtual network. Contoso also wants to minimize cost and complexity. Contoso should do which of the following?


<i class='far fa-square'></i> &nbsp;&nbsp;Implement a hub-and-spoke network.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Implement Virtual WAN with secured hubs (Azure Firewall).

<i class='far fa-square'></i> &nbsp;&nbsp;Use only one very large virtual network. Deploy Azure Firewall into that virtual network and all services for that region.

<i class='far fa-square'></i> &nbsp;&nbsp;Deploy Virtual WAN.
<br />
<br />
<br />

####  2. Contoso is creating its global connectivity subscription to support Azure services across six regions globally in the US, Europe, Australia, and India. Contoso will mostly be using PaaS services with Private Link but also about 3,000 virtual machines per region. Contoso has small colocation facilities and datacenters in 20 countries on every populated continent. Contoso currently uses multiple MPLS networks from three providers for datacenter and large office connectivity. Contoso requires firewalls for all traffic moving between on-premises and Azure, and it needs to minimize latency for these connections. Contoso will have many applications that need to communicate across Azure regions and cross-premises. Contoso also wants to minimize cost and complexity. Contoso should:


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Implement a hub-and-spoke network, with Azure Firewall in the hubs and a hub in each of the six Azure regions.

<i class='far fa-square'></i> &nbsp;&nbsp;Implement Virtual WAN with secured hubs (Azure Firewall) in each of the six Azure regions.

<i class='far fa-square'></i> &nbsp;&nbsp;Use only one large virtual network in each region. Deploy Azure Firewall into that virtual network and all services for that region.

<i class='far fa-square'></i> &nbsp;&nbsp;Deploy Virtual WAN.
<br />
<br />
<br />
