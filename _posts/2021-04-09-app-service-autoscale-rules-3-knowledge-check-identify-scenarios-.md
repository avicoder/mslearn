---
    layout: post
    title: Dynamically meet changing web app performance requirements with autoscale rules - Knowledge Check - Identify suitable scenarios for autoscaling
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/app-service-autoscale-rules/3-knowledge-check-identify-scenarios/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/app-service-autoscale-rules.svg">
####  1. Which of these statements best describes autoscaling?


<i class='far fa-square'></i> &nbsp;&nbsp;Autoscaling is a scale up/scale down solution. It migrates an application to more powerful hardware during periods of high demand, and moves it back to less powerful hardware when demand drops.

<i class='far fa-square'></i> &nbsp;&nbsp;Autoscaling requires an administrator to actively monitor the workload on a system. If the workload increases and response times start to drop, the administrator can trigger autoscaling to help increase the throughput of the system.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Autoscaling is a scale out/scale in solution. The system can scale out when specified resource metrics indicate increasing usage, and scale in when these metrics drop.

<i class='far fa-square'></i> &nbsp;&nbsp;Autoscaling is an ideal solution for handling sudden bursts of activity that last for a few minutes.

<i class='far fa-square'></i> &nbsp;&nbsp;Scaling in and out provides better availability than autoscaling.
<br />
<br />
<br />

####  2. Autoscaling enables a system to predict the resources that will be required to handle an increasing workload.


<i class='far fa-square'></i> &nbsp;&nbsp;True

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;False
<br />
<br />
<br />

####  3. Which of these scenarios is a suitable candidate for autoscaling?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The number of users requiring access to an application varies according to a regular schedule. For example, more users use the system on a Friday than other days of the week.

<i class='far fa-square'></i> &nbsp;&nbsp;The system is subject to a sudden influx of requests that grinds your system to a halt. The workload has increased exponentially and there appears to be no reason for this surge of activity.

<i class='far fa-square'></i> &nbsp;&nbsp;Over time, your service is becoming more popular, and you need to handle the increasing traffic.

<i class='far fa-square'></i> &nbsp;&nbsp;Your organization is running a promotion and expects to see increased traffic to their web site for the next couple of weeks. Ensure sufficient resources are available to handle the demand expected when the promotion starts.
<br />
<br />
<br />
