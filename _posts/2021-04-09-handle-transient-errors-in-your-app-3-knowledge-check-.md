---
    layout: post
    title: Handle transient errors in your app 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/handle-transient-errors-in-your-app/3-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/handle-transient-errors-in-your-app.svg">
####  1. Why should an app back-off from trying to read from a database that is responding too slowly?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The database could be under heavy load, so backing-off could give it time to recover.

<i class='far fa-square'></i> &nbsp;&nbsp;The database server is being upgraded, so retrying will cause the upgrade to fail.

<i class='far fa-square'></i> &nbsp;&nbsp;Backing-off means that the app can retry the operation quicker, to get a faster response.
<br />
<br />
<br />

####  2. Why is it important that operations are idempotent if they're being retried?


<i class='far fa-square'></i> &nbsp;&nbsp;Retrying the operation leads to data being incremented the number of times the operation is processed successfully.

<i class='far fa-square'></i> &nbsp;&nbsp;If the operation is going to be retried, and previous operations have all failed, the data will be incorrect.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;If the operation is going to be retried, and previous operations have been successful, the data won't be duplicated or corrupted.
<br />
<br />
<br />

####  3. What's the main difference between permanent and terminal errors?


<i class='far fa-square'></i> &nbsp;&nbsp;Permanent errors need to be handled and then quit the app. Terminal errors automatically quit the app.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Permanent errors can be handled by using data from elsewhere. Terminal errors mean the app can't continue and should quit.

<i class='far fa-square'></i> &nbsp;&nbsp;Permanent errors are unrecoverable, log the data and quit. Terminal errors shouldn't log data and quit.
<br />
<br />
<br />
