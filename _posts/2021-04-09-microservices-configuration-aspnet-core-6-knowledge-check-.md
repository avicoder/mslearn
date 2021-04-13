---
    layout: post
    title: Implement feature flags in a cloud-native ASP.NET Core microservices app 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/microservices-configuration-aspnet-core/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/microservices-configuration-aspnet-core.svg">
####  1. What's the key abstraction that supports the configuration system in ASP.NET Core apps?


<i class='far fa-square'></i> &nbsp;&nbsp;Feature Management library

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Configuration provider

<i class='far fa-square'></i> &nbsp;&nbsp;ConfigMap

<i class='far fa-square'></i> &nbsp;&nbsp;Azure App Configuration
<br />
<br />
<br />

####  2. The Feature Management library's <feature> Tag Helper serves what purpose in ASP.NET Core Razor views?


<i class='far fa-square'></i> &nbsp;&nbsp;The <feature> tag is irrelevant to ASP.NET Core Razor views. It's used in an Angular view to render content based on a feature's state.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The <feature> tag conditionally renders content based on a feature's state in ASP.NET Core Razor views.

<i class='far fa-square'></i> &nbsp;&nbsp;The <feature> tag defines a new feature flag, in the Razor markup, to be used in Azure App Configuration.

<i class='far fa-square'></i> &nbsp;&nbsp;The <feature> tag defines a new feature flag, in the project file, to be used in Azure App Configuration.
<br />
<br />
<br />

####  3. Which of the following statements is NOT true about Azure App Configuration?


<i class='far fa-square'></i> &nbsp;&nbsp;App Configuration provides a service to centrally manage app settings and feature flags.

<i class='far fa-square'></i> &nbsp;&nbsp;The easiest way to add an App Configuration store to your .NET Core app is through a client library provided by Microsoft.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;App Configuration doesn't encrypt your app settings at rest.

<i class='far fa-square'></i> &nbsp;&nbsp;App Configuration can be integrated with the .NET Feature Management library.
<br />
<br />
<br />
