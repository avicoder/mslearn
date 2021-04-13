---
    layout: post
    title: Load balance your web service traffic with Application Gateway - Route traffic with Application Gateway
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/load-balance-web-traffic-with-application-gateway/2-routing-traffic-with-application-gateway/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/load-balance-web-traffic-with-application-gateway.svg">
####  1. Which criteria does Application Gateway use to route requests to a web server?


<i class='far fa-square'></i> &nbsp;&nbsp;The IP address of the web server that is the target of the request

<i class='far fa-square'></i> &nbsp;&nbsp;The region in which the servers hosting the web application are located.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The hostname, port, and path in the URL of the request
<br />
<br />
<br />

####  2. Which load balancing strategy does Application Gateway implement?


<i class='far fa-square'></i> &nbsp;&nbsp;Application Gateway selects the server in the backend pool that currently has the lightest load.

<i class='far fa-square'></i> &nbsp;&nbsp;Application Gateway polls each server in the backend pool in turn, and sends the request to the first server that responds.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Application Gateway follows a round-robin approach, distributing requests to each available server in a backend pool in turn.
<br />
<br />
<br />
