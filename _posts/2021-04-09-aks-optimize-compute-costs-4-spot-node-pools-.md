---
    layout: post
    title: Optimize compute costs on Azure Kubernetes Service (AKS) - Configure multiple node pools by using AKS spot node pools with the cluster autoscaler
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-optimize-compute-costs/4-spot-node-pools/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/optimize-compute-costs-on-azure-kubernetes-service.svg">
####  1. Suppose you have a stateless service that processes online orders and runs on an Azure Kubernetes Service (AKS) cluster. You decide to use spot node pools on the AKS cluster to optimize compute costs on the cluster. How do you add spot node pools to an AKS cluster?


<i class='far fa-square'></i> &nbsp;&nbsp;Run the az aks update command and specify the convert-to-spot-vm parameter.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the Azure portal to add a new spot node pool to the AKS cluster.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run the az aks nodepool add command to add a new spot user node pool to the AKS cluster.
<br />
<br />
<br />

####  2. For the service described in the preceding question, which eviction policy is the most cost-effective option for configuring the spot node pool?


<i class='far fa-square'></i> &nbsp;&nbsp;Use the az aks update command to set the --eviction-policy to Hibernate.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the az aks update command to set the --eviction-policy to Delete.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the az aks update command and set the --eviction-policy to Deallocate.
<br />
<br />
<br />

####  3. For the service described in the preceding questions, how do you ensure that workloads are scheduled on the nodes of the spot user node pool?


<i class='far fa-square'></i> &nbsp;&nbsp;AKS ensures that new workloads are always scheduled on spot node pools in an AKS cluster. This behavior is the default, and no additional configuration is required.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure the workload manifest file with a nodeTaint value of kubernetes.azure.com/scalesetpriority=spot:NoSchedule

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Configure the workload manifest file with a toleration that uses the key kubernetes.azure.com/scalesetpriority and applies the NoSchedule effect. This configuration tells the system to schedule the workload on the nodes in the spot node pool.
<br />
<br />
<br />
