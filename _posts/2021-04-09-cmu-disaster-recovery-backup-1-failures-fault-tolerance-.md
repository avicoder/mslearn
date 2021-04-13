---
    layout: post
    title: Disaster recovery and backup - Failures and fault tolerance
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-disaster-recovery-backup/1-failures-fault-tolerance/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-admin/cmu-disaster-recovery-backup.svg">
####  1. Which of the following test scenarios will not help test the resiliency and readiness of a cloud service?


<i class='far fa-square'></i> &nbsp;&nbsp;Randomly turning off VM instances that make up the service

<i class='far fa-square'></i> &nbsp;&nbsp;Turning off an entire data center or availability zone

<i class='far fa-square'></i> &nbsp;&nbsp;Randomly deleting the files that back up the production database of the main web server

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;All of these tests ensure the resiliency of the cloud service
<br />
<br />
<br />

####  2. An organization deploys a solution consisting of a Web site and a database to the cloud. It also deploys a replica solution to take over in the event that the primary solution fails. In the background, each request that reaches the primary Web site is forwarded to (and also processed by) the secondary Web site. Responses from the secondary site are ignored, while responses from the primary site are transmitted back to the client. While no attempt is made to synchronize the actions of the primary site and its replica, the intent is to make sure that the secondary database mirrors the primary database as closely as possible. Which resource replication strategy does this represent?


<i class='far fa-square'></i> &nbsp;&nbsp;Active replication

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Semi-active replication

<i class='far fa-square'></i> &nbsp;&nbsp;Passive replication

<i class='far fa-square'></i> &nbsp;&nbsp;Semi-passive replication
<br />
<br />
<br />
