---
    layout: post
    title: Introduction to open-source database migration on Azure 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/introduction-open-source-database-migration-azure/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/introduction-to-open-source-database-migration-on-azure.svg">
####  1. You want to create a highly available database system that requires the minimum of administrative time to run. Should you use an IaaS or a PaaS approach?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a IaaS approach. Create a set of virtual machines to run your system, and connect them using a virtual network. You have full control over the databases and server running on these virtual machines.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use a PaaS approach. For example, run a PostgreSQL database using Azure Database for PostgreSQL.

<i class='far fa-square'></i> &nbsp;&nbsp;Use either
<br />
<br />
<br />

####  2. You want to run a MySQL database in an IaaS environment in which you'll create new instances as quickly as possible. Should you use virtual machines or containers?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use containers.

<i class='far fa-square'></i> &nbsp;&nbsp;Use virtual machines.

<i class='far fa-square'></i> &nbsp;&nbsp;Use either.
<br />
<br />
<br />

####  3. You want to migrate individual applications and users running specific workloads to the cloud as an initial step in migrating your system. If successful, you'll migrate further workloads until the entire system has been moved. How would you do this?


<i class='far fa-square'></i> &nbsp;&nbsp;Perform an online migration of the database.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Follow a piecemeal approach to migration.

<i class='far fa-square'></i> &nbsp;&nbsp;Perform an offline migration of the database.
<br />
<br />
<br />

####  4. Which migration approach for an on-premises MySQL database to Azure SQL Database takes the least amount of administrative effort?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the SQL Server Migration Assistant.

<i class='far fa-square'></i> &nbsp;&nbsp;Do an online migration using the Azure Database Migration Service.

<i class='far fa-square'></i> &nbsp;&nbsp;Upload the data to Azure storage, and configure Azure SQL Database to read the data from the storage account.
<br />
<br />
<br />
