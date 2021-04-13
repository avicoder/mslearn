---
    layout: post
    title: Calculate job WIP in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/calculate-job-wip/6-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/calculate-job-wip.svg">
####  1. You calculated WIP for a new job for the first time by running the Job Calculate WIP function. While analyzing the results, you realize that the job is set up with the wrong WIP method of Cost Value instead of Sales Value. What do you need to do to calculate WIP for the correct WIP method?


<i class='far fa-square'></i> &nbsp;&nbsp;Use the Copy Job function to create a new job, update the WIP method for the new job, and then run the Job Calculate WIP function for the new job.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Job Post WIP to G/L function and make sure that the Reverse Only field is selected. Next, update the WIP method on the job card and then run the Job Calculate WIP function again.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Job Calculate WIP function and make sure that the Reverse Only field is selected. Next, update the WIP method on the job card and then run the Job Calculate WIP function again, but without the Reverse Only field selected.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run the Delete WIP Entries function, change the WIP method on the job card, and then run the Job Calculate WIP function.
<br />
<br />
<br />

####  2. How can you post WIP entries to the general ledger?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run the Job Calculate WIP function and then the Job Post WIP to G/L function.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Job Calculate WIP function, which calculates the WIP amounts and automatically posts them to the general ledger.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Job Post WIP to G/L function, which calculates the WIP amounts and automatically posts them to the general ledger.

<i class='far fa-square'></i> &nbsp;&nbsp;Select an option in the Post WIP to G/L Recurrence field on the Jobs Setup page, for example, Month. This approach ensures that every month, WIP is automatically posted to the general ledger.
<br />
<br />
<br />
