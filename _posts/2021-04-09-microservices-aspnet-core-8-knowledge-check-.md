---
    layout: post
    title: Create and deploy a cloud-native ASP.NET Core microservice 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/microservices-aspnet-core/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/microservices-aspnet-core.svg">
####  1. In a microservices architecture, how do individual services access their data?


<i class='far fa-square'></i> &nbsp;&nbsp;Data is stored in a master data store with which all microservices interact.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Each microservice implements its own data store that's best optimized for its workload, storage needs, and read/write patterns.

<i class='far fa-square'></i> &nbsp;&nbsp;Services don't directly store data. They send data to an event bus and it's processed by a data repository service.
<br />
<br />
<br />

####  2. For the ASP.NET Core Health Checks middleware, the code services.AddHealthChecks().AddCheck("coupon-self", () => HealthCheckResult.Healthy()); in Startup.ConfigureServices serves what purpose?


<i class='far fa-square'></i> &nbsp;&nbsp;Configures a Kubernetes liveness probe using HTTP GET.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Registers a health check, named coupon-self, that returns the HTTP success code to the endpoint configured in the Startup.Configure method.

<i class='far fa-square'></i> &nbsp;&nbsp;Maps a health endpoint that is accessible at <your-service>/liveness.
<br />
<br />
<br />

####  3. What is the benefit of using Azure Container Registry?


<i class='far fa-square'></i> &nbsp;&nbsp;Container Registry allows public access to container images. Consequently, developers can access the images without authenticating.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Container Registry is a private container registry and provides granular access control for development teams.

<i class='far fa-square'></i> &nbsp;&nbsp;Container Registry can support both public and private container registries.
<br />
<br />
<br />
