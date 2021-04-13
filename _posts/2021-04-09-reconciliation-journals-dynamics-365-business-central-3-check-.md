---
    layout: post
    title: Set up payment reconciliation journals in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/reconciliation-journals-dynamics-365-business-central/3-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/reconciliation-journals-dynamics-365-business-central.svg">
####  1. What do you need to set up to enable automatic applications if small payment differences exist?


<i class='far fa-square'></i> &nbsp;&nbsp;On the general ledger setup, enter the Payment Tolerance \% or Payment Tolerance Amount fields.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the bank account card, select the Match Tolerance Type and the Match Tolerance value fields.

<i class='far fa-square'></i> &nbsp;&nbsp;On the Sales & Receivables Setup page, enter the Max. Payment Diff. Allowed field.

<i class='far fa-square'></i> &nbsp;&nbsp;On the customer card, enter the Payment Tolerance \% or Payment Tolerance Amount fields.
<br />
<br />
<br />

####  2. You modified the payment application rules, but now you want to revert to the default set of payment application rules. What is the best way to do this?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the action menu of the Payment Application Rules window, select Restore Default Rules.

<i class='far fa-square'></i> &nbsp;&nbsp;Use RapidStart Services to restore the default rules.

<i class='far fa-square'></i> &nbsp;&nbsp;Open a company that has the default rules and export them to Microsoft Excel. In the company where you want to replace the modified rules with the default ones, use the Import from Excel function on the Payment Application Rules page.

<i class='far fa-square'></i> &nbsp;&nbsp;You must reenter them manually.
<br />
<br />
<br />
