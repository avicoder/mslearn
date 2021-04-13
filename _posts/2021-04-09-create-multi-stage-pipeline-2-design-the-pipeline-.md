---
    layout: post
    title: Create a multistage pipeline by using Azure Pipelines - Design the pipeline
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-multi-stage-pipeline/2-design-the-pipeline/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/azure-devops/create-multi-stage-pipeline.svg">
####  1. Your pipeline includes many tests and quality checks that take several minutes to finish. Which kind of trigger is best for running tests only on code that a peer has reviewed?


<i class='far fa-square'></i> &nbsp;&nbsp;A build completion trigger

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A CI trigger or PR trigger

<i class='far fa-square'></i> &nbsp;&nbsp;A scheduled trigger
<br />
<br />
<br />

####  2. What's the best way to pause the pipeline until an approver signs off on a change?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use a release approval.

<i class='far fa-square'></i> &nbsp;&nbsp;Install a Marketplace extension that provides Azure Pipelines tasks that can pause the pipeline.

<i class='far fa-square'></i> &nbsp;&nbsp;Ask your approver to look at the change. Then manually trigger the pipeline to run.
<br />
<br />
<br />

####  3. You want to deploy your web app to the Test environment each time a build finishes. What's the easiest way to set up the process?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a scheduled trigger.

<i class='far fa-square'></i> &nbsp;&nbsp;Watch for build notification emails and manually trigger your build when the other one finishes successfully.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use a build completion trigger.
<br />
<br />
<br />
