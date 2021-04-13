---
    layout: post
    title: Manage and control traffic flow in your Azure deployment with routes - What is an NVA?
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/control-network-traffic-flow-with-routes/4-network-virtual-appliances/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/control-network-traffic-flow-with-routes.svg">
####  1. What is the main benefit of using a network virtual appliance?


<i class='far fa-square'></i> &nbsp;&nbsp;To control outbound access to the internet.

<i class='far fa-square'></i> &nbsp;&nbsp;To load balance incoming traffic from the internet across multiple Azure virtual machines and across two regions for DR purposes.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To control incoming traffic from the perimeter network and allow only traffic that meets security requirements to pass through.

<i class='far fa-square'></i> &nbsp;&nbsp;To control who can access Azure resources from the perimeter network.
<br />
<br />
<br />

####  2. How might you deploy a network virtual appliance?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can configure a Windows virtual machine and enable IP forwarding after routing tables, user-defined routes, and subnets have been updated. Or you can use a partner image from Azure Marketplace.

<i class='far fa-square'></i> &nbsp;&nbsp;Using Azure CLI, deploy a Linux virtual machine in Azure, connect this virtual machine to your production virtual network, and assign a public IP address.

<i class='far fa-square'></i> &nbsp;&nbsp;Using the Azure portal, deploy a Windows 2016 Server instance. Next, using Azure Application Gateway, add the Windows 2016 Server instance as a target endpoint.

<i class='far fa-square'></i> &nbsp;&nbsp;Download a virtual appliance from Azure Marketplace and configure the appliance to connect to the production and perimeter networks.
<br />
<br />
<br />
