---
    layout: post
    title: Work with data source limits (delegation limits) in a Power Apps canvas app  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-with-data-source-limits-powerapps-canvas-app/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/data-source-limits.svg">
####  1. What happens when you delegate a function to a data source?


<i class='far fa-square'></i> &nbsp;&nbsp;Only the first 500 records return from the data source.

<i class='far fa-square'></i> &nbsp;&nbsp;The first 500 records process and then the matches are returned.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The data source processes the function against all of the data and returns only the matches.

<i class='far fa-square'></i> &nbsp;&nbsp;A maximum of 2000 records return.
<br />
<br />
<br />

####  2. What should you do when you see the warning triangle and blue line that delegation is not occurring?


<i class='far fa-square'></i> &nbsp;&nbsp;Adjust the row limit from 500 to 2000 records and then ignore the warning.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Determine if the limited returned data will cause issues for the functionality of your app and design your app as appropriate.

<i class='far fa-square'></i> &nbsp;&nbsp;Ignore it, warnings are not a big deal and the user will know how to deal with the warning.

<i class='far fa-square'></i> &nbsp;&nbsp;Try a different function because Power Apps will not run if there are warnings.
<br />
<br />
<br />

####  3. When combining delegable and non-delegable functions in a formula what happens?


<i class='far fa-square'></i> &nbsp;&nbsp;The data is only limited for the non-delegable portion, which in no way affects the delegable functions.

<i class='far fa-square'></i> &nbsp;&nbsp;You cannot combine delegable and non-delegable functions in the same formula.

<i class='far fa-square'></i> &nbsp;&nbsp;Power Apps will generate errors only if the app has more than 2000 records.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The delegable functions may become non-delegable reducing the amount of data returned by the formula.
<br />
<br />
<br />
