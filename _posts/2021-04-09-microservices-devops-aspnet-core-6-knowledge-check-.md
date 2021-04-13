---
    layout: post
    title: Deploy a cloud-native ASP.NET Core microservice with GitHub Actions 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/microservices-devops-aspnet-core/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/microservices-devops-aspnet-core.svg">
####  1. Without using the GitHub Actions Marketplace, where should sensitive information, such as credentials, be stored for Actions?


<i class='far fa-square'></i> &nbsp;&nbsp;appsettings.json

<i class='far fa-square'></i> &nbsp;&nbsp;web.config

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Key Vault

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;GitHub secrets
<br />
<br />
<br />

####  2. What is the purpose of creating an Azure Active Directory service principal for use in GitHub Actions?


<i class='far fa-square'></i> &nbsp;&nbsp;The service principal is for storing application logs.

<i class='far fa-square'></i> &nbsp;&nbsp;The service principal is the name of the AKS resource.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The service principal is the GitHub Action's identity for performing tasks in Azure.

<i class='far fa-square'></i> &nbsp;&nbsp;The service principal is the web URL of the app.
<br />
<br />
<br />

####  3. During deployment, what is the purpose of Kubernetes creating a new container while the old one is still running?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Avoid downtime

<i class='far fa-square'></i> &nbsp;&nbsp;Scaling up

<i class='far fa-square'></i> &nbsp;&nbsp;Redundancy

<i class='far fa-square'></i> &nbsp;&nbsp;Scaling out
<br />
<br />
<br />
