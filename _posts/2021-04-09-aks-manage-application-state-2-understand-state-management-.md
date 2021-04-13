---
    layout: post
    title: Deploy and manage a stateful application by using Azure Cosmos DB and Azure Kubernetes Service - Understand state management in Kubernetes
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-manage-application-state/2-understand-state-management/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aks-manage-application-state.svg">
####  1. What is the persistent state of an application?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It's the type of state that continues to exist even after the application has been closed.

<i class='far fa-square'></i> &nbsp;&nbsp;It's the state that's stored in memory or locally on the container.

<i class='far fa-square'></i> &nbsp;&nbsp;It's all the disks and volumes that compose the application.
<br />
<br />
<br />

####  2. How does Kubernetes handle states?


<i class='far fa-square'></i> &nbsp;&nbsp;It doesn't. Kubernetes don't have state-handling features.

<i class='far fa-square'></i> &nbsp;&nbsp;It externalizes the state to another node outside the cluster.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It uses a set of objects called PersistentVolume and PersistentVolumeClaim.
<br />
<br />
<br />

####  3. What's a best practice for handling state in Kubernetes applications?


<i class='far fa-square'></i> &nbsp;&nbsp;Store the state inside Kubernetes only.

<i class='far fa-square'></i> &nbsp;&nbsp;Remove any possible state and use only ephemeral storage.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Delegate the state management to external specialized solutions.
<br />
<br />
<br />
