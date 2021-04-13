---
    layout: post
    title: Get started with workflows in Dynamics 365 for Customer Engagement  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/get-started-workflows-customer-engagement-apps/06-check-your-knowledge/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/get-started-with-workflows-in-dynamics-365.svg">
####  1. A workflow process is deactivated. What happens to workflows currently in process at the time of deactivation?


<i class='far fa-square'></i> &nbsp;&nbsp;Current workflows enter a waiting status and can be resumed later.

<i class='far fa-square'></i> &nbsp;&nbsp;Asynchronous workflows are paused, changes made by synchronous workflows are rolled back.

<i class='far fa-square'></i> &nbsp;&nbsp;Current workflows are canceled.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Nothing. Workflows previously triggered will run to completion or cancelation.
<br />
<br />
<br />

####  2. Which type of workflow runs independent of other workflows and plugins?


<i class='far fa-square'></i> &nbsp;&nbsp;Real-Time workflow

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Background workflow

<i class='far fa-square'></i> &nbsp;&nbsp;Parent workflow

<i class='far fa-square'></i> &nbsp;&nbsp;Child workflow
<br />
<br />
<br />

####  3. For a workflow with a scope of business unit, which record field indicates the records that will be exposed to the workflow?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Owner

<i class='far fa-square'></i> &nbsp;&nbsp;Territory

<i class='far fa-square'></i> &nbsp;&nbsp;Business unit

<i class='far fa-square'></i> &nbsp;&nbsp;Scope
<br />
<br />
<br />

####  4. When an asynchronous workflow is triggered by a change in data, whose security roles are used to give the security context?


<i class='far fa-square'></i> &nbsp;&nbsp;The owner of the record.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The owner of the workflow.

<i class='far fa-square'></i> &nbsp;&nbsp;The system administrator.

<i class='far fa-square'></i> &nbsp;&nbsp;The user modifying the record.
<br />
<br />
<br />

####  5. You have a workflow with a wait condition that waits for a specific status reason value. What step would you use to ensure that the process does not wait indefinitely?


<i class='far fa-square'></i> &nbsp;&nbsp;Synchronous Wait step using process Start time property.

<i class='far fa-square'></i> &nbsp;&nbsp;Change Status step to update status reason value to the one matching wait condition.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Parallel Wait step using Timeout property of the process.

<i class='far fa-square'></i> &nbsp;&nbsp;You cannot simultaneously wait on multiple conditions.
<br />
<br />
<br />
