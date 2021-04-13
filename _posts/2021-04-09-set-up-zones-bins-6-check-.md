---
    layout: post
    title: Set up zones and bins in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/set-up-zones-bins/6-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/set-up-zones-bins.svg">
####  1. You are setting up Warehouse Management System for a company that sells food. Some items must be stored in freezers, while others can be stored in bins without specific conditions. You have set up the freezers as bins, but what do you need to configure to make sure that the program suggests a freezer on the put-away document of a frozen item?


<i class='far fa-square'></i> &nbsp;&nbsp;On the Bin Types page, you must set up a bin type FROZEN and then assign it to the freezers and to the items that must be stored in frozen conditions.

<i class='far fa-square'></i> &nbsp;&nbsp;You must set up a zone FROZEN and assign that zone to the items that must be stored in frozen conditions. All bins in the FROZEN zone are automatically available to store items in frozen conditions.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the Warehouse Classes page, you must set up a warehouse class FROZEN and then assign it to the freezers and to the items that must be stored in frozen conditions.

<i class='far fa-square'></i> &nbsp;&nbsp;You can manage this scenario with dimensions. You must create a dimension, for example WAREHOUSE CONDITIONS, and dimension values like FROZEN, COLD, and so on. To store an item in frozen conditions, you would assign the FROZEN dimension value to both the item and bin.
<br />
<br />
<br />

####  2. If an item has a fixed place in the warehouse, what do you need to do to link the item to that place?


<i class='far fa-square'></i> &nbsp;&nbsp;On the item card, expand the Warehouse FastTab, and in the Bin Code field, enter the fixed bin for the item.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the Bins page, select the fixed bin for the item and then open the Bin Content page. On the Bin Content page, enter the item number and select the Fixed option.

<i class='far fa-square'></i> &nbsp;&nbsp;On the Bins page, enter the item number and select the Fixed option.

<i class='far fa-square'></i> &nbsp;&nbsp;On the first put-away document for the item, enter the bin and select the Fixed option. After registering the put-away, the bin is automatically set as fixed for the item.
<br />
<br />
<br />
