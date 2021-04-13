---
    layout: post
    title: Application scalability on AKS with HorizontalPodAutoscalers - Understand scaler configurations
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-application-autoscaling-native/4-concepts-scaling-fine-tune/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/generic-badge.svg">
####  1. What does the stabilization window mean?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The amount of time the HPA will look back to the metrics API to get stable data.

<i class='far fa-square'></i> &nbsp;&nbsp;The cooldown period before scaling up or down again.

<i class='far fa-square'></i> &nbsp;&nbsp;The number of seconds to wait before the HPA can start working.
<br />
<br />
<br />

####  2. What are the three values for selectPolicies?


<i class='far fa-square'></i> &nbsp;&nbsp;Average, Disabled, and Max

<i class='far fa-square'></i> &nbsp;&nbsp;Min, Max, and Deactivated

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Min, Max and Disabled
<br />
<br />
<br />

####  3. When should you define behavior to your HPA?


<i class='far fa-square'></i> &nbsp;&nbsp;On every created HPA since the key is required.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When we want to fine-tune the HPA behavior.

<i class='far fa-square'></i> &nbsp;&nbsp;To fine-tune the deployment behavior when scaling.
<br />
<br />
<br />
