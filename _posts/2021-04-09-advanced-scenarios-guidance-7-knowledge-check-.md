---
    layout: post
    title: Configure advanced scenarios in Microsoft Cloud App Security 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/advanced-scenarios-guidance/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/generic-badge.svg">
####  1. You’ve blocked access to a suspect website for your entire organization. However, a user finds that they can still access the site by using their iPhone. How can you prevent this access?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use Intune to deploy Microsoft Defender for Endpoint for iOS to all iPhones in your organization.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a custom indicator of compromise that blocks the website.

<i class='far fa-square'></i> &nbsp;&nbsp;Install a new log collector to protect iOS devices.
<br />
<br />
<br />

####  2. Your organization has recently acquired a new company and you want to investigate Shadow IT that is in use on the company’s network. You have installed a log collector but it cannot connect to Microsoft Cloud App Security. Which of the following conditions might cause this problem?


<i class='far fa-square'></i> &nbsp;&nbsp;You have used a Linux container for the log collector. Use a Windows container instead

<i class='far fa-square'></i> &nbsp;&nbsp;The Cloud App Security portal doesn’t trust the root certificate authority installed on the log collector

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The log collector doesn’t trust the root certificate authority installed on the proxy server
<br />
<br />
<br />

####  3. A new phishing attack relies on users being misled into downloading a compiled executable file and running it. How can you ensure that Microsoft Cloud App Security blocks this new file as quickly as possible?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use a new file policy to implement a custom indicator of compromise.

<i class='far fa-square'></i> &nbsp;&nbsp;Write a custom app that uses the Microsoft Cloud App Security REST API to define a custom indicator of compromise.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure all log collectors to block the executable file.
<br />
<br />
<br />

####  4. You’re using the Advanced hunting tool in the Microsoft 365 security center to find information about a suspicious activity certain users have been executing. Which of these languages should you use to write the query?


<i class='far fa-square'></i> &nbsp;&nbsp;Transact SQL

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Kusto

<i class='far fa-square'></i> &nbsp;&nbsp;XML
<br />
<br />
<br />

####  5. You have used curl to issue the following REST request but have been denied access. What should you do to fix the problem? curl -XGET 'https://<portal_url>/api/v1/alerts'


<i class='far fa-square'></i> &nbsp;&nbsp;Include a filter in your query

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Include an authorization token in your command

<i class='far fa-square'></i> &nbsp;&nbsp;Send the query from custom code instead of from the curl command-line tool.
<br />
<br />
<br />
