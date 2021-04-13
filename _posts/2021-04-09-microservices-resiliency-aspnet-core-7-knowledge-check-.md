---
    layout: post
    title: Implement resiliency in a cloud-native ASP.NET Core microservice 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/microservices-resiliency-aspnet-core/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/microservices-resiliency-aspnet-core.svg">
####  1. What's the primary goal when implementing a resiliency solution for an app?


<i class='far fa-square'></i> &nbsp;&nbsp;Make the app error-free.

<i class='far fa-square'></i> &nbsp;&nbsp;Handling user errors transparently.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Handling transient infrastructure failures.

<i class='far fa-square'></i> &nbsp;&nbsp;Handling major infrastructure failures.
<br />
<br />
<br />

####  2. Which of the following sentences is correct?


<i class='far fa-square'></i> &nbsp;&nbsp;Polly is the best option to handle failures, but it requires a significant amount of work.

<i class='far fa-square'></i> &nbsp;&nbsp;Linkerd can be implemented with little effort, but it only handles TCP connection failures.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Polly and Linkerd can have complementary roles, depending on the context.
<br />
<br />
<br />

####  3. Which of the following components isn't needed to achieve a resilient app in Kubernetes?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;CI/CD pipelines.

<i class='far fa-square'></i> &nbsp;&nbsp;Health check probes for services.

<i class='far fa-square'></i> &nbsp;&nbsp;Failure handling code for complex database transactions.

<i class='far fa-square'></i> &nbsp;&nbsp;Network-related resiliency infrastructure.
<br />
<br />
<br />

####  4. Which of the following statements isn't true of Linkerd?


<i class='far fa-square'></i> &nbsp;&nbsp;It can adjust retries and timeouts adapting to the current cluster state.

<i class='far fa-square'></i> &nbsp;&nbsp;It can monitor the traffic between pods.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It must be included in the app's code.

<i class='far fa-square'></i> &nbsp;&nbsp;It monitors all incoming and outgoing connections.
<br />
<br />
<br />

####  5. Which of the following statements isn't true of Polly?


<i class='far fa-square'></i> &nbsp;&nbsp;It can handle retries with exponential back-off.

<i class='far fa-square'></i> &nbsp;&nbsp;It can ensure resiliency for complex database transactions.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It doesn't require app code changes.

<i class='far fa-square'></i> &nbsp;&nbsp;It must be configured via code for every HttpClient.
<br />
<br />
<br />
