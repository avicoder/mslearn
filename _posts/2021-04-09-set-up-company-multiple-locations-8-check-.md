---
    layout: post
    title: Set up a company with multiple locations in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/set-up-company-multiple-locations/8-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/set-up-company-multiple-locations.svg">
####  1. What is the best way to set up location MAIN as the centralized warehouse in which items are purchased in Business Central?


<i class='far fa-square'></i> &nbsp;&nbsp;For each vendor, on the Receiving FastTab, set the Location Code field to MAIN.

<i class='far fa-square'></i> &nbsp;&nbsp;On the Inventory Setup page, select MAIN in the Location Code field.

<i class='far fa-square'></i> &nbsp;&nbsp;Assign MAIN as the purchase location on the User Setup page for each purchaser.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the Shipping FastTab of the Company Information page, select MAIN in the Location Code field.
<br />
<br />
<br />

####  2. How can you prevent users from posting item transactions with a blank location?


<i class='far fa-square'></i> &nbsp;&nbsp;By setting up one or multiple locations. If at least one location is set up in Business Central, locations will be mandatory by default.

<i class='far fa-square'></i> &nbsp;&nbsp;The first time that you use a location in a sales or purchase order, it automatically becomes mandatory.

<i class='far fa-square'></i> &nbsp;&nbsp;Block the blank location by opening the location card for the unspecified (blank) location and then selecting the Blocked field.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the Inventory Setup page, select the Location Mandatory field.
<br />
<br />
<br />
