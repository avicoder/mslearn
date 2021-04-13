---
    layout: post
    title: Protect, monitor, and tune a migrated database 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/protect-monitor-tuning-migrated-database/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/protecting-monitoring-and-tuning-a-migrated-database.svg">
####  1. You're writing a script that uses the Azure CLI to create and configure an Azure Database for MySQL service. You need to allow access to the service for other Azure services. Which IP address range should you specify in the az mysql server firewall-rule create command?


<i class='far fa-square'></i> &nbsp;&nbsp;Set the start-ip-address parameter to 0.0.0.0, and the end-ip-address parameter to 255.255.255.255.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set the start-ip-address and end-ip-address parameters to 0.0.0.0.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the start-ip-address and end-ip-address parameters to the range defined by the subnet that contains your resources.
<br />
<br />
<br />

####  2. How do you change the server parameters for Azure Database for MySQL?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the Server parameters page for the server in the Azure portal.

<i class='far fa-square'></i> &nbsp;&nbsp;You can't change server parameters. The server is managed entirely by Azure.

<i class='far fa-square'></i> &nbsp;&nbsp;Connect to the server using MySQL Workbench and use the System Variables page to modify the server settings.
<br />
<br />
<br />

####  3. You're using Query Performance Insight to track the performance of queries running on your server. You notice that the wait statistics for one query show a significant number of lengthy IO waits. What might cause this?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;This could be due to a poorly designed query, an inefficient join operation, or a full table scan incurred because of a missing index.

<i class='far fa-square'></i> &nbsp;&nbsp;This could be caused by a high volume of network activity.

<i class='far fa-square'></i> &nbsp;&nbsp;This might be the result of connection throttling, if the server is attempting to handle a large number of concurrent requests.
<br />
<br />
<br />
