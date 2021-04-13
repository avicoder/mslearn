---
    layout: post
    title: Design a geographically distributed application - Design a geographically distributed application architecture
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/design-a-geographically-distributed-application/4-geo-distributed-app/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/design-geographically-distributed-application-social.png">
####  1. Which components of the shipping company architecture should be explicitly copied to another region?


<i class='far fa-square'></i> &nbsp;&nbsp;Azure DNS and Azure AD

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Azure App Service, Azure Function App, Redis Cache, queue

<i class='far fa-square'></i> &nbsp;&nbsp;Azure DNS, Azure AD, Azure Storage
<br />
<br />
<br />

####  2. Complete this sentence: If a regional failure takes out Azure Storage, data loss...


<i class='far fa-square'></i> &nbsp;&nbsp;Won't occur because all data is automatically copied to a secondary region.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;May briefly occur because data is copied asynchronously.

<i class='far fa-square'></i> &nbsp;&nbsp;May briefly occur but the data can be restored from the master
<br />
<br />
<br />
