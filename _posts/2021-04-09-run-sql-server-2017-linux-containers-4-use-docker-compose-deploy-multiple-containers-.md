---
    layout: post
    title: Run SQL Server 2019 on Linux containers - Create custom images
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/run-sql-server-2017-linux-containers/4-use-docker-compose-deploy-multiple-containers/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/sqlserver/run-sql-server-2017-on-linux-containers.svg">
####  1. You want to create a new container image based on the SQL Server on Linux image. You're using Docker to host your containers. Which directive should you use in the Dockerfile to specify this parent?


<i class='far fa-square'></i> &nbsp;&nbsp;The COPY directive

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The FROM directive

<i class='far fa-square'></i> &nbsp;&nbsp;The ENV directive
<br />
<br />
<br />

####  2. You include this line in a Dockerfile: '#CMD [/opt/mssql/bin/sqlservr]'. When you build the image, SQL Server is not run. What must you do to fix the problem?


<i class='far fa-square'></i> &nbsp;&nbsp;Use #RUN instead of #CMD.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use CMD instead of #CMD.

<i class='far fa-square'></i> &nbsp;&nbsp;Use #ENV instead of #CMD.
<br />
<br />
<br />
