---
    layout: post
    title: Work with master data in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-with-master-data-business-central/7-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-with-master-data-business-central.svg">
####  1. Which trigger ensures that the number series functionality is applied during master record or document creation?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;OnInsert trigger

<i class='far fa-square'></i> &nbsp;&nbsp;OnModify trigger

<i class='far fa-square'></i> &nbsp;&nbsp;OnValidate trigger

<i class='far fa-square'></i> &nbsp;&nbsp;OnRename trigger
<br />
<br />
<br />

####  2. How can you make sure that a setup table only holds one record?


<i class='far fa-square'></i> &nbsp;&nbsp;The setup card page contains code in the appropriate triggers to block any insertions or deletions and, when you open the page, it inserts a record if none is present.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The setup card page uses the InsertAllowed and DeleteAllowed properties with a value of No. and, when you open the page, it inserts a record if none is present.

<i class='far fa-square'></i> &nbsp;&nbsp;A function in a codeunit uses events to monitor the setup card page to make sure that exactly one record is always in the setup table.

<i class='far fa-square'></i> &nbsp;&nbsp;You can set the OnlyAllowOneRecord table property to True.
<br />
<br />
<br />

####  3. How do you define that a decimal field should have at least two decimal places?


<i class='far fa-square'></i> &nbsp;&nbsp;Set the DecimalPlaces property to 2-2.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the DecimalPlaces property to 0-2.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the MinDecimalPlaces property to 2.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set the DecimalPlaces property to 2.
<br />
<br />
<br />
