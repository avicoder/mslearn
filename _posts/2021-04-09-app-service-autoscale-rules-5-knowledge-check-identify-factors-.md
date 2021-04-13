---
    layout: post
    title: Dynamically meet changing web app performance requirements with autoscale rules - Knowledge Check - Identify factors for implementing autoscaling
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/app-service-autoscale-rules/5-knowledge-check-identify-factors/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/app-service-autoscale-rules.svg">
####  1. You have defined an autoscale condition with four autoscale rules. The first rule scales out when the CPU utilization reaches 70 percent. The second rule scales back in when the CPU utilization drops below 50 percent. The third rule scales out if memory occupancy exceeds 75 percent. The fourth rule scales back in when memory occupancy falls below 50 percent. When will the system scale-out?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When CPU utilization reaches 70 percent, or memory occupancy exceeds 75 percent

<i class='far fa-square'></i> &nbsp;&nbsp;When CPU utilization reaches 70 percent, and memory occupancy exceeds 75 percent

<i class='far fa-square'></i> &nbsp;&nbsp;You can't do this with a single autoscale condition. An autoscale condition can only contain autoscale rules that use the same metric
<br />
<br />
<br />

####  2. An autoscale rule defines a scale-out action that increases the instance count when the disk queue length exceeds 10. The system scaled out two minutes ago, but the disk queue length is still over 10. When will the system scale-out again?


<i class='far fa-square'></i> &nbsp;&nbsp;The autoscale rule will trigger another autoscale action immediately, and will continue doing so until the disk queue length drops below 10, or the maximum number of instances have been created.

<i class='far fa-square'></i> &nbsp;&nbsp;The autoscale rule will not run again until the system has scaled back in.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The autoscale rule will not trigger the action again until the cool down period for the rule has expired. If the disk queue length is still over 10 at this time, the action will be performed.
<br />
<br />
<br />
