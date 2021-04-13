---
    layout: post
    title: Secure your apps by using the sidecar configuration in Azure Container Instances 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/secure-apps-azure-container-instances-sidecar/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/generic-badge.svg">
####  1. What Azure Container Instance feature can you use to perform initialization tasks required by your application?


<i class='far fa-square'></i> &nbsp;&nbsp;Other Azure Container Instances running in parallel

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Init Containers

<i class='far fa-square'></i> &nbsp;&nbsp;Modify the application code to perform initialization
<br />
<br />
<br />

####  2. How do sidecar containers communicate with the main application container?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Sidecar containers can communicate with other containers in the same container group using 127.0.0.1 as destination IP address.

<i class='far fa-square'></i> &nbsp;&nbsp;Sidecar containers can use DNS to find out the address of others containers in the container group.

<i class='far fa-square'></i> &nbsp;&nbsp;Not possible, because containers in a container group are isolated from each other.
<br />
<br />
<br />

####  3. Which images can be used for sidecar containers?


<i class='far fa-square'></i> &nbsp;&nbsp;Sidecar containers can be created from the same image as the main application container.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Sidecar containers can be created from any container image, from any image repository.

<i class='far fa-square'></i> &nbsp;&nbsp;Sidecar containers can be created from any container image, but all containers in the container group need to be instantiated from the same image repository.
<br />
<br />
<br />

####  4. Which IP address will an Azure Container Instance receive, when deployed in a Virtual Network?


<i class='far fa-square'></i> &nbsp;&nbsp;The Azure Container Instance will receive a private IP address in the subnet where it is deployed, as well as a public IP address.

<i class='far fa-square'></i> &nbsp;&nbsp;The Azure Container Instance will receive a public IP address.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The Azure Container Instance will receive a private IP address in the subnet where it is deployed.
<br />
<br />
<br />

####  5. From where can Azure Container Instances deployed in a Virtual Network be accessed?


<i class='far fa-square'></i> &nbsp;&nbsp;Only from inside the Virtual Network.

<i class='far fa-square'></i> &nbsp;&nbsp;From inside the Virtual Network and from other peered Virtual Networks.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;From inside the Virtual Network, from other peered Virtual Networks, and from on-premises network connected over VPN or ExpressRoute.
<br />
<br />
<br />
