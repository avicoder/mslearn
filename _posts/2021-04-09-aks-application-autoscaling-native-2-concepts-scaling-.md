---
    layout: post
    title: Application scalability on AKS with HorizontalPodAutoscalers - Concepts of scalability
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-application-autoscaling-native/2-concepts-scaling/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/generic-badge.svg">
####  1. What is horizontal scaling?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When the application is replicated in order to sustain a heavier load.

<i class='far fa-square'></i> &nbsp;&nbsp;Adding more RAM to the VM.

<i class='far fa-square'></i> &nbsp;&nbsp;Rendering the application stateless so it can be used without a persistent storage.
<br />
<br />
<br />

####  2. Why is it important to have a resource request set on pods bound to an HPA?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Because this is the only way to calculate the resource utilization.

<i class='far fa-square'></i> &nbsp;&nbsp;It's not important, but it's recommended so the application doesn't starve.

<i class='far fa-square'></i> &nbsp;&nbsp;So the HPA knows when to stop scaling a resource based on the resources available in the cluster.
<br />
<br />
<br />

####  3. Why is vertical scaling less recommended for stateless applications?


<i class='far fa-square'></i> &nbsp;&nbsp;Because vertical scaling duplicates the applications and this is harder on stateless apps.

<i class='far fa-square'></i> &nbsp;&nbsp;Because it requires a stateful application to be vertically scaled.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Because it's cheaper to duplicate a stateless application than increase the resources on its VM.
<br />
<br />
<br />
