---
    layout: post
    title: Build an Azure Digital Twins graph for a chocolate factory production line 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/develop-with-azure-digital-twins/build-azure-digital-twins-graph-for-chocolate-factory/knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/iot/build-azure-digital-twins-graph-for-chocolate-factory.svg">
####  1. What are the fields of a Digital Twins Definition Language (DTDL) interface?


<i class='far fa-square'></i> &nbsp;&nbsp;@type, name, schema

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Property, Telemetry, Component, Relationship

<i class='far fa-square'></i> &nbsp;&nbsp;@id, @type, @context, displayName, contents

<i class='far fa-square'></i> &nbsp;&nbsp;primitive types, and Object, Map, Enum
<br />
<br />
<br />

####  2. What is the difference between a DTDL property and DTDL telemetry?


<i class='far fa-square'></i> &nbsp;&nbsp;There is no significant difference.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Properties are expected to have storage, that can be written to if necessary. Telemetry is a stream of values.

<i class='far fa-square'></i> &nbsp;&nbsp;Properties do not change, Telemetry changes continuously.

<i class='far fa-square'></i> &nbsp;&nbsp;Telemetry is for IoT devices, Properties are for digital twins.
<br />
<br />
<br />

####  3. You have a set of models, some of which contain a property called Temperature. Which of the following queries return all models with a temperature less than 65 degrees?


<i class='far fa-square'></i> &nbsp;&nbsp;SELECT * FROM DigitalTwins T WHERE T.Temp < 65

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;SELECT * FROM DigitalTwins T WHERE T.Temperature < 65

<i class='far fa-square'></i> &nbsp;&nbsp;SELECT * FROM DigitalTwins WHERE IS_DEFINED(Temperature)

<i class='far fa-square'></i> &nbsp;&nbsp;if (Temperature < 65) return model.name;
<br />
<br />
<br />

####  4. What is a distinction between a FROM clause in a SQL-type language and a FROM clause in the Azure Digital Twins query language?


<i class='far fa-square'></i> &nbsp;&nbsp;In the ADT query language, you can only have one JOIN statement in the FROM clause, while in a SQL-type language, you can have multiple.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In the ADT query language, each expression in a FROM clause is not a table. Instead, the FROM clause expresses a cross-entity relationship traversal, and is written with an Azure Digital Twins version of JOIN.

<i class='far fa-square'></i> &nbsp;&nbsp;In the ADT query language, the FROM clause is used to specify which table to select data from, while in a SQL-type language, each expression in a FROM clause expresses a cross-entity relationship traversal.
<br />
<br />
<br />
