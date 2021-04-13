---
    layout: post
    title: Migrate on-premises PostgreSQL databases to Azure Database for PostgreSQL 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/migrate-on-premises-postgresql-databases/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/migrate-onpremises-postgresql-db-azure-db.svg">
####  1. You have customers running applications that access your PostgreSQL database. The operations these applications perform are typically queries that generate reports. These customers are located in Australia, Europe, and the United States. Your corporate headquarters is in the United States, this is where you insert, update, and delete most of the data. How can you minimize query latency for your customers?


<i class='far fa-square'></i> &nbsp;&nbsp;Run copies of the database using Azure Database for PostgreSQL in Australia, Europe, and America. At regular intervals, back up the data at each site, and restore it on the other two sites.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Implement read replicas with Azure Database for PostgreSQL. Make the United States office the master server, and replicate the data to replicas running in Australia and Europe.

<i class='far fa-square'></i> &nbsp;&nbsp;Host your database in an instance of the Azure Database for PostgreSQL service, and scale up to the maximum number of virtual processor cores.
<br />
<br />
<br />

####  2. You want to use the pgAdmin utility to monitor your database running in Azure Database for PostgreSQL. You're attempting to connect from your desktop computer. You're using the correct server name, protocol (SSL), username, and password, but you receive an error. What might the problem be?


<i class='far fa-square'></i> &nbsp;&nbsp;You can't use pgAdmin to monitor a database running in Azure Database for PostgreSQL.

<i class='far fa-square'></i> &nbsp;&nbsp;The computer running the pgAdmin utility must be in the same virtual network as the Azure Database for PostgreSQL service instance.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Check that you've added a firewall rule to your Azure Database for PostgreSQL service that allows connections from your desktop computer.
<br />
<br />
<br />

####  3. You want to perform an online migration of an on-premises PostgreSQL database to Azure Database for PostgreSQL. Which tools should you use?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The Azure Database Migration Service, running using the Premium pricing tier.

<i class='far fa-square'></i> &nbsp;&nbsp;The pg_dump and pg_restore utilities.

<i class='far fa-square'></i> &nbsp;&nbsp;The pg_dump and psql utilities.
<br />
<br />
<br />

####  4. You need to configure applications so they connect to your databases in Azure Database for PostgreSQL. Where can you find this database connection information?


<i class='far fa-square'></i> &nbsp;&nbsp;On the Connection security page for your Azure Database for PostgreSQL service in the Azure portal.

<i class='far fa-square'></i> &nbsp;&nbsp;It will be the same as the connection information used to connect to databases in your on-premises PostgreSQL servers, but the server name will have the "Azure" prefix.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the Connection strings page for your Azure Database for PostgreSQL service in the Azure portal.
<br />
<br />
<br />
