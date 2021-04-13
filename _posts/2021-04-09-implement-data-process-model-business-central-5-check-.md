---
    layout: post
    title: Implement the data process model in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/implement-data-process-model-business-central/5-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/implement-data-process-model-business-central.svg">
####  1. What are configuration tables in Business Central?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Static or slowly changing tables where users enter information once and then rarely, if ever, change it

<i class='far fa-square'></i> &nbsp;&nbsp;Primary work tables for users, where they regularly enter information

<i class='far fa-square'></i> &nbsp;&nbsp;Tables whose information is generated automatically by the application during posting and similar processes

<i class='far fa-square'></i> &nbsp;&nbsp;Setup tables
<br />
<br />
<br />

####  2. Which three tables make up a journal?


<i class='far fa-square'></i> &nbsp;&nbsp;Journal Template, Journal Setup, and Journal Line

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Journal Template, Journal Batch, and Journal Line

<i class='far fa-square'></i> &nbsp;&nbsp;Journal Template, Journal Batch, and Journal Entry

<i class='far fa-square'></i> &nbsp;&nbsp;Journal Master, Journal Batch, and Journal Line
<br />
<br />
<br />

####  3. What type of table is the Document Header table?


<i class='far fa-square'></i> &nbsp;&nbsp;Batch posting table

<i class='far fa-square'></i> &nbsp;&nbsp;Configuration table

<i class='far fa-square'></i> &nbsp;&nbsp;Posted transaction table

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Operational transaction table
<br />
<br />
<br />

####  4. When is the OnInsert trigger run?


<i class='far fa-square'></i> &nbsp;&nbsp;This table trigger runs when a user inserts a new record into a table. The code in the trigger runs after the record is inserted into the table.

<i class='far fa-square'></i> &nbsp;&nbsp;This table trigger runs when a user inserts a new record into a table. The code in the trigger runs only if you use the Insert(TRUE) parameter.

<i class='far fa-square'></i> &nbsp;&nbsp;This table trigger runs when a user inserts a new record into a table. The code in the trigger runs after the record is inserted into the table.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;This table trigger runs when a user inserts a new record into a table from a page. The code in the trigger runs before the record is inserted into the table.
<br />
<br />
<br />
