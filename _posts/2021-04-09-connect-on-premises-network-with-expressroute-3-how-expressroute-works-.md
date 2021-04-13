---
    layout: post
    title: Connect your on-premises network to the Microsoft global network by using ExpressRoute - How Azure ExpressRoute works
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/connect-on-premises-network-with-expressroute/3-how-expressroute-works/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/connect-on-premises-network-with-expressroute.svg">
####  1. What is Microsoft peering?


<i class='far fa-square'></i> &nbsp;&nbsp;It provides a direct connection from your on-premises network to an Azure datacenter.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It enables you to connect your on-premises network to Office 365 services and Dynamics 365.

<i class='far fa-square'></i> &nbsp;&nbsp;It provides a connection between your on-premises network and an ExpressRoute provider.

<i class='far fa-square'></i> &nbsp;&nbsp;It provides a point-to-site connection for computers in your on-premises location to Office 365 services.
<br />
<br />
<br />

####  2. What is an ExpressRoute circuit?


<i class='far fa-square'></i> &nbsp;&nbsp;An ExpressRoute circuit implements a site-to-site connection across a VPN connection to an Azure datacenter.

<i class='far fa-square'></i> &nbsp;&nbsp;An ExpressRoute circuit is a direct hard-wired connection between your on-premises datacenter and an Azure datacenter.

<i class='far fa-square'></i> &nbsp;&nbsp;A backup service that provides connectivity to the Microsoft cloud if your VPN connection fails.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A circuit provides a physical connection for transmitting data through the ExpressRoute provider's edge routers to the Microsoft edge routers.
<br />
<br />
<br />

####  3. What security benefits does Azure ExpressRoute provide?


<i class='far fa-square'></i> &nbsp;&nbsp;An ExpressRoute connection is automatically encrypted, to help protect traffic that passes across the internet to the Microsoft cloud.

<i class='far fa-square'></i> &nbsp;&nbsp;The speed at which data traverses an ExpressRoute connection makes it impossible to intercept by network monitors and packet sniffers.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;ExpressRoute uses a dedicated, private network to connect to the Microsoft cloud. Traffic doesn't traverse the public internet, so it's difficult to intercept.

<i class='far fa-square'></i> &nbsp;&nbsp;ExpressRoute uses a proprietary transmission protocol that constantly varies, so it's difficult to intercept traffic.
<br />
<br />
<br />
