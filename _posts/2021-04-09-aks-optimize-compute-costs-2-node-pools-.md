---
    layout: post
    title: Optimize compute costs on Azure Kubernetes Service (AKS) - Configure multiple nodes and enable scale-to-zero by using AKS
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-optimize-compute-costs/2-node-pools/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/optimize-compute-costs-on-azure-kubernetes-service.svg">
####  1. Suppose your software solution has three critical components. The first component is a web application. The second is a service that processes online orders. The third is a video-rendering and analysis service that runs only as needed and that requires GPU-based VMs. To optimize cost, how many node pools would you deploy in an Azure Kubernetes Service (AKS) cluster to manage the solution?


<i class='far fa-square'></i> &nbsp;&nbsp;Deploy a single user node pool when you create the AKS cluster. Assign three nodes per component by using GPU-based VMs, for a total of nine nodes in the node pool. Enable autoscaling on the node pool.

<i class='far fa-square'></i> &nbsp;&nbsp;Deploy three user node pools on the AKS cluster. Create the first and second node pools with standard-sized virtual machines (VMs), and create the third node pool with specialized, GPU-based VMs. Enable the cluster autoscaler on all three node pools.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Deploy three user node pools on the AKS cluster. Create the first and second node pools with standard-sized VMs and the third node pool with specialized, GPU-based VMs. Enable autoscaling on the first two node pools. Scale the GPU-based node pool manually.
<br />
<br />
<br />

####  2. Complete the following statement. The Kubernetes cluster autoscaler scales...


<i class='far fa-square'></i> &nbsp;&nbsp;...the number of workload replicas on an AKS cluster. It monitors the Metrics API every 30 seconds to decide whether your application needs additional instances to meet demand.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;...the number of nodes by monitoring the Metrics API. It scales the number of nodes up or down based on computing resources required.

<i class='far fa-square'></i> &nbsp;&nbsp;...the number of node pools on an AKS cluster. It monitors the Metrics API every 30 seconds to decide whether your application needs additional node pools to meet demand.
<br />
<br />
<br />
