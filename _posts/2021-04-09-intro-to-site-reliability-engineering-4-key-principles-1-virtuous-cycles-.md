---
    layout: post
    title: Introduction to Site Reliability Engineering (SRE) - Key SRE principles and practices- virtuous cycles
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/intro-to-site-reliability-engineering/4-key-principles-1-virtuous-cycles/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/intro-to-site-reliability-engineering-sre.svg">
####  1. What does SLI stand for (in an SRE context)?


<i class='far fa-square'></i> &nbsp;&nbsp;Standard Level Indicator

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Service Level Indicator

<i class='far fa-square'></i> &nbsp;&nbsp;Safe Load Indicator

<i class='far fa-square'></i> &nbsp;&nbsp;System Level Interface
<br />
<br />
<br />

####  2. What does SLO stand for (in an SRE context)?


<i class='far fa-square'></i> &nbsp;&nbsp;Service Level Outcome

<i class='far fa-square'></i> &nbsp;&nbsp;Standard Line Operations

<i class='far fa-square'></i> &nbsp;&nbsp;Service Load Objective

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Service Level Objective
<br />
<br />
<br />

####  3. If you exhaust your error budget for a service, what should you do?


<i class='far fa-square'></i> &nbsp;&nbsp;Immediately restart the service involved so it can be brought back into compliance

<i class='far fa-square'></i> &nbsp;&nbsp;Put a hold on further releases of that software until the service has returned to the agreed upon level of reliability

<i class='far fa-square'></i> &nbsp;&nbsp;Immediately redirect engineering resources associated with this service from feature development to fixing the reliability problem

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;React in the service- or organizationally-specific way previously agreed upon when creating that error budget
<br />
<br />
<br />

####  4. If you exceed your error budget for a service, what should you do?


<i class='far fa-square'></i> &nbsp;&nbsp;Speed up the release cadence for that service

<i class='far fa-square'></i> &nbsp;&nbsp;Focus more on feature development for that service and deploy those features faster

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It depends
<br />
<br />
<br />

####  5. When a downtime or other incident occurs, should you immediately terminate the people involved?


<i class='far fa-square'></i> &nbsp;&nbsp;Yes, the person or people who made the mistake should always take responsibility for their actions and pay the consequences

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No, except under certain rare and extraordinary circumstances
<br />
<br />
<br />
