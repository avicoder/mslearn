---
    layout: post
    title: Execute an Azure Function with triggers - Summary
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/execute-azure-function-with-triggers/9-summary/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/execute-azure-function-with-triggers.svg">
####  1. A CRON expression is a string that consists of six fields that represent a set of times. The order of the six fields in Azure is: {second} {minute} {hour} {day} {month} {day of the week}. Suppose you needed a CRON expression that meant "every day", what special character would you put in the {day of the week} position?


<i class='far fa-square'></i> &nbsp;&nbsp;/

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;*

<i class='far fa-square'></i> &nbsp;&nbsp;,

<i class='far fa-square'></i> &nbsp;&nbsp;‐
<br />
<br />
<br />

####  2. Suppose your Azure Function has a blob trigger associated with it and you want it to execute only when png images are uploaded. Which of the following blob trigger Path values should you use?


<i class='far fa-square'></i> &nbsp;&nbsp;samples-workitems/{name}

<i class='far fa-square'></i> &nbsp;&nbsp;samples-workitems/{name}/png

<i class='far fa-square'></i> &nbsp;&nbsp;samples-workitems/{name}?png

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;samples-workitems/{name}.png
<br />
<br />
<br />

####  3. True or false: an Azure Function can have multiple triggers associated with it?


<i class='far fa-square'></i> &nbsp;&nbsp;True

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;False
<br />
<br />
<br />
