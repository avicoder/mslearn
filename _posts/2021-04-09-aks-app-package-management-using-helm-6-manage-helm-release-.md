---
    layout: post
    title: Application and package management using Helm - Manage a Helm release
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/aks-app-package-management-using-helm/6-manage-helm-release/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/app-package-management-using-helm.svg">
####  1. Suppose a software solution has two critical components. The first component is a web application. The second is a service that processes online orders. The two components are both part of an online order processing pipeline, but doesn't have a dependency on each other. Which strategy would fit the deployment of these two applications best using Helm?


<i class='far fa-square'></i> &nbsp;&nbsp;Create a single Helm chart that for both applications, but don't set either chart as a dependency of the other.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create two separate Helm charts. One for each of the applications.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a single Helm chart for both applications, and set the service that process the orders as a dependency chart.
<br />
<br />
<br />

####  2. Suppose a software solution makes use of website as one of its critical components. The website is the only component that depends on a caching service. Which strategy would fit the deployment of these two applications best using Helm?


<i class='far fa-square'></i> &nbsp;&nbsp;Create two separate Helm charts. One for each of the applications.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a single Helm chart to deploy the website. Deploy the caching service as a separate component by using deployment manifest files.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a single Helm chart for both applications, and set the caching service as a dependency chart.
<br />
<br />
<br />
