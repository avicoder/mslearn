---
    layout: post
    title: Correct entries in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/correct-entries/5-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/correct-entries.svg">
####  1. After posting the depreciation for January 2020, you realize that you have used the wrong posting date. Consequently, the January 2020 depreciation amounts for all fixed assets should be corrected. What is the best way to accomplish this task?


<i class='far fa-square'></i> &nbsp;&nbsp;From the G/L Registers, use the Reverse Transaction function to reverse the depreciation posting of January 2020. Then, use the Calculate Depreciation batch job to recalculate the depreciations.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;From the Depreciation Book for which the depreciations were posted, use the Cancel FA Ledger Entries batch job to cancel the January 2020 depreciations. Then, use the Calculate Depreciation batch job to recalculate the depreciations.

<i class='far fa-square'></i> &nbsp;&nbsp;In the Fixed Assets list, select the fixed assets for which you want to cancel the depreciations then, in the ribbon, select the Cancel Entries function to cancel the January 2020 depreciations. Next, use the Calculate Depreciation batch job to recalculate the depreciations.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the Copy Depreciation Book batch job to copy the depreciations for January 2020. Then, use the Calculate Depreciation batch job to recalculate the depreciations.
<br />
<br />
<br />

####  2. You accidentally disposed of a fixed asset by selling it through a sales invoice and you need to cancel the sale. Why can't you complete this task with the Reverse Transaction function?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Because the sale was posted from a sales invoice and you can't use the Reverse Transaction function for entries that are posted from a document.

<i class='far fa-square'></i> &nbsp;&nbsp;You can only cancel a fixed asset sale by running the Cancel FA Entries function.

<i class='far fa-square'></i> &nbsp;&nbsp;The Reverse Transaction function never posts to the fixed asset ledger.

<i class='far fa-square'></i> &nbsp;&nbsp;The Reverse Transaction function doesn't post general VAT/Tax entries.
<br />
<br />
<br />
