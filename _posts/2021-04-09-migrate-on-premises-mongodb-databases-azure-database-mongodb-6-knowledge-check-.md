---
    layout: post
    title: Migrate on-premises MongoDB databases to Cosmos DB 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/migrate-on-premises-mongodb-databases-azure-database-mongodb/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/migrate-on-premises-mongodb-databases-to-cosmos-db.svg">
####  1. How do you share throughput between containers?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Specify database throughput.

<i class='far fa-square'></i> &nbsp;&nbsp;Specify container throughput.

<i class='far fa-square'></i> &nbsp;&nbsp;Specify logical partition throughput.
<br />
<br />
<br />

####  2. You have decided to distribute your database over multiple regions to decrease latency for users. What is the effect of the availability SLA?


<i class='far fa-square'></i> &nbsp;&nbsp;It remains at 99.99\%.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It increases to 99.999\%.

<i class='far fa-square'></i> &nbsp;&nbsp;It increases to 99.9999\%
<br />
<br />
<br />

####  3. You need specific connection strings for your applications, so that they use your security protocols. Where can you find this information?


<i class='far fa-square'></i> &nbsp;&nbsp;In your Cosmos DB account, in Overview.

<i class='far fa-square'></i> &nbsp;&nbsp;In your Cosmos DB account, in Settings, and then Network.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In your Cosmos DB account, in Settings, and then Connection String.
<br />
<br />
<br />

####  4. You have all your users in one region and need to maximize availability. How should you achieve this?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Replicate data to at least two regions.

<i class='far fa-square'></i> &nbsp;&nbsp;Have a single copy of your data and premium level backups.

<i class='far fa-square'></i> &nbsp;&nbsp;Replicate data within your region.
<br />
<br />
<br />

####  5. Database level throughput is most appropriate for most migrations, but you have identified that collection level throughput is most appropriate long term. How should you configure your throughput?


<i class='far fa-square'></i> &nbsp;&nbsp;Specify database throughput.

<i class='far fa-square'></i> &nbsp;&nbsp;Specify collection throughput, but temporarily change to database throughput for the migration.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Specify collection throughput.
<br />
<br />
<br />
