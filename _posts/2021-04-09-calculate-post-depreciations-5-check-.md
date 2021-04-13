---
    layout: post
    title: Calculate and post depreciations in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/calculate-post-depreciations/5-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/calculate-post-depreciations.svg">
####  1. When running the Calculate Depreciation batch job, you want the system to use 30 days in the depreciation calculation for all fixed assets. What is the best way to achieve this objective?


<i class='far fa-square'></i> &nbsp;&nbsp;You don’t need to do anything specific. By default, 30 days is used in the depreciation calculation for all fixed assets.

<i class='far fa-square'></i> &nbsp;&nbsp;In the Calculate Depreciation batch job, in the Starting Date field, enter the first day of the month. Then, in the Ending Date field, enter the last day of the month.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In the Calculate Depreciation batch job, in the Force No. of Days field, enter 30.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Calculation Depreciation batch job, and in the FA G/L journal or the FA journal, before posting, update the No. of Depreciation Days for all fixed assets to 30.
<br />
<br />
<br />

####  2. You are using two depreciation books, the COMPANY depreciation book with G/L integration enabled and the TAX depreciation book. You want to calculate depreciation for both. How can you accomplish this task?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You need to run the Calculate Depreciation batch job separately for each depreciation book.

<i class='far fa-square'></i> &nbsp;&nbsp;If you run the Calculate Depreciation batch job for the default depreciation book (COMPANY in this example), the program automatically calculates depreciation for all other depreciation books.

<i class='far fa-square'></i> &nbsp;&nbsp;If you run the Calculate Depreciation batch job for the default depreciation book (COMPANY in this example), the program automatically calculates depreciation for all other depreciation books that have the Part of Duplication List field selected.

<i class='far fa-square'></i> &nbsp;&nbsp;You need to first run the Calculate Depreciation batch job for the default depreciation book (COMPANY in this example) to generate journal lines in the fixed asset journal. Next, on the fixed asset journal, select Copy Lines to Other Depreciation Books and then post the journal.
<br />
<br />
<br />
