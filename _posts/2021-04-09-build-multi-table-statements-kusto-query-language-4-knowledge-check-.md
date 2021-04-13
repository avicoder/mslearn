---
    layout: post
    title: Build multi-table statements using KQL 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-multi-table-statements-kusto-query-language/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/build-multi-table-statements-in-kql.svg">
####  1. Which join flavor contains a row in the output for every combination of matching rows from left and right?


<i class='far fa-square'></i> &nbsp;&nbsp;kind=leftouter

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;kind=inner

<i class='far fa-square'></i> &nbsp;&nbsp;kind=fullouter
<br />
<br />
<br />

####  2. When using the join operator, how do you specify fields from each table?


<i class='far fa-square'></i> &nbsp;&nbsp;$1.columname and $2.columnname

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;$left.columname and $right.columnname

<i class='far fa-square'></i> &nbsp;&nbsp;$inner.columname and $outer.columnname
<br />
<br />
<br />

####  3. When you union two tables, the two tables need matching columns?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No.

<i class='far fa-square'></i> &nbsp;&nbsp;Yes.

<i class='far fa-square'></i> &nbsp;&nbsp;Only when the project operator is used.
<br />
<br />
<br />
