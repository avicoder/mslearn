---
    layout: post
    title: Build a Power BI report with Business Central data  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-power-bi-report/9-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/build-power-bi-report.svg">
####  1. What is the difference between a fact table and a dimensional table in a star schema?  


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Dimension tables describe business entities and Fact tables store observations or events.

<i class='far fa-square'></i> &nbsp;&nbsp;Dimension tables store observations or events and Fact tables describe business entities.

<i class='far fa-square'></i> &nbsp;&nbsp;Dimension tables are linked to dimensions in Business Central and Fact tables describe ledger entry tables.

<i class='far fa-square'></i> &nbsp;&nbsp;Dimension tables contain less then 20 records and Fact tables can store many thousands of records.
<br />
<br />
<br />

####  2. What is the purpose of query shaping in Power BI?


<i class='far fa-square'></i> &nbsp;&nbsp;During or after importing data from a data source like Business Central, you can adjust the data to meet your needs. To shape data, you provide Power Query Editor with step-by-step instructions for adjusting the data while loading and presenting it. Shaping will affect the original data source, so be careful.

<i class='far fa-square'></i> &nbsp;&nbsp;Before importing data from a data source like Business Central, you need to adjust the data to meet your needs. To shape data, you provide Power Query Editor with step-by-step instructions for adjusting the data in your data source, while loading and presenting it.

<i class='far fa-square'></i> &nbsp;&nbsp;Query shaping means you need to provide clear and easy to understand names of the query and all its fields, so that the Power Query Editor can load them during data import.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;During or after importing data from a data source like Business Central, you can adjust the data to meet your needs. To shape data, you provide Power Query Editor with step-by-step instructions for adjusting the data while loading and presenting it. Shaping does not affect the original data source, only this view of the data.
<br />
<br />
<br />

####  3. Why do you need to add a Date table to your data model in Power BI Desktop?  


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You don't need to add a Date table in Power BI Desktop if there is at least one data field in your model, Power BI Desktop will auto create hidden date tables when required. However sometimes you need to create your own table so you can control the date hierarchies created.

<i class='far fa-square'></i> &nbsp;&nbsp;You can't manually add a Date table in Power BI Desktop. If there is at least one data field in your model, Power BI Desktop will auto create hidden date tables when required.

<i class='far fa-square'></i> &nbsp;&nbsp;You don't need to add a Date table in Power BI Desktop. Instead, you need to enable the add-date-table-to-model option in Power Query editor.

<i class='far fa-square'></i> &nbsp;&nbsp;If you don't add a data table in Power BI Desktop, then you won't be able to visualize information using a timeline visual.
<br />
<br />
<br />

####  4. What is DAX?


<i class='far fa-square'></i> &nbsp;&nbsp;DAX helps you create new visuals from data already in your model.

<i class='far fa-square'></i> &nbsp;&nbsp;DAX helps you edit existing information from in your model.

<i class='far fa-square'></i> &nbsp;&nbsp;DAX helps you create new import connectors for your data, in the Power Query Editor.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;DAX helps you create new information from data already in your model.
<br />
<br />
<br />
