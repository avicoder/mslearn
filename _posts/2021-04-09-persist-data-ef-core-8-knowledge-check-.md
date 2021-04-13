---
    layout: post
    title: Persist and retrieve relational data with Entity Framework Core 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/persist-data-ef-core/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/persist-data-ef-core.svg">
####  1. In an entity class, what is the property naming convention for a primary key?


<i class='far fa-square'></i> &nbsp;&nbsp;Key or <entity name>Key

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Id or <entity name>Id

<i class='far fa-square'></i> &nbsp;&nbsp;<entity name>
<br />
<br />
<br />

####  2. Within the underlying EF Core architecture, the Database Provider component serves what purpose?


<i class='far fa-square'></i> &nbsp;&nbsp;Translates object graph changes to SQL.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Manages the connection to the database engine and executes generated SQL in the database.

<i class='far fa-square'></i> &nbsp;&nbsp;Represents an active connection to a database.
<br />
<br />
<br />

####  3. Suppose you want to write a read-only query. How do you indicate to EF Core that object graph change tracking is unnecessary?


<i class='far fa-square'></i> &nbsp;&nbsp;Set the entity's state to EntityState.Unchanged.

<i class='far fa-square'></i> &nbsp;&nbsp;Chain the ToListAsync() method call to the LINQ query or fluent method chain.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Chain the AsNoTracking() method call to the entity object.
<br />
<br />
<br />
