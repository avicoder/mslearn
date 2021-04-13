---
    layout: post
    title: Deploy a containerized application on Azure Kubernetes Service - Enable network access to an application
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-deploy-container-app/6-expose-app/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aks-deploy-container-app.svg">
####  1. What's the purpose of the ClusterIP service type?


<i class='far fa-square'></i> &nbsp;&nbsp;To freeze the cluster's IP so that we can access it directly.

<i class='far fa-square'></i> &nbsp;&nbsp;To make services available to other Azure Kubernetes Service clusters within the Azure network.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To group pods into one single IP that's only available within the cluster.
<br />
<br />
<br />

####  2. What's the purpose of the LoadBalancer service type?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To expose the service externally by using Azure's load-balancing solution.

<i class='far fa-square'></i> &nbsp;&nbsp;To balance the flow of internal communication in the cluster.

<i class='far fa-square'></i> &nbsp;&nbsp;To group several different pods into a reverse proxy that's used internally in the cluster.
<br />
<br />
<br />

####  3. What is an ingress?


<i class='far fa-square'></i> &nbsp;&nbsp;A workload to create DNS zone records in Azure via API access to the cloud.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A workload to define the set of rules that allow external applications into the cluster.

<i class='far fa-square'></i> &nbsp;&nbsp;Groups pods into one single IP address so they don't lose their IPs when they're destroyed.
<br />
<br />
<br />
