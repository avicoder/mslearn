---
    layout: post
    title: Azure Kubernetes Service deployment pipeline and GitHub Actions - Understand application images
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-deployment-pipeline-github-actions/5-application-images/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aks-deployment-pipeline-github-actions.svg">
####  1. What is a Docker image?


<i class='far fa-square'></i> &nbsp;&nbsp;A zipped directory with code we can download and run on any platform or computer by using Docker.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A standalone, lightweight package that includes all that's needed to run the application in a container.

<i class='far fa-square'></i> &nbsp;&nbsp;A snapshot of our current working directory hosted in the cloud.
<br />
<br />
<br />

####  2. What are the main advantages of using a Docker image?


<i class='far fa-square'></i> &nbsp;&nbsp;Despite being much heavier than standard VMs, Docker images are simpler and faster to deploy.

<i class='far fa-square'></i> &nbsp;&nbsp;The only advantage is that images can be hosted by using container registers, so they're easier to download and run.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Images are smaller and much faster than a VM, and they don't contain useless OS data.
<br />
<br />
<br />
