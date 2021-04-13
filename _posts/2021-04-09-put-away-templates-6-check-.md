---
    layout: post
    title: Set up put-away templates in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/put-away-templates/6-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/put-away-templates.svg">
####  1. Item 1908-S is stored in location MAIN and location WEST. Both locations are set up with directed put-away and pick. The item has only a fixed bin in location MAIN. You configured two put-away templates, FIXED and FLOAT. The FIXED template searches for fixed bins first and then for floating bins. The FLOAT template only searches for floating bins. Most items in both locations have a fixed bin. How would you set up the put-away template for this item?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;On the Bin Policies FastTab for both locations, select FIXED in the Put-away Template Code field. Create stockkeeping units for the item. On the stockkeeping unit card for location WEST, enter FLOAT in the Put-away Template Code field. On the stockkeeping unit card for MAIN, leave the Put-away Template Code field blank.

<i class='far fa-square'></i> &nbsp;&nbsp;On the Bin Policies FastTab for both locations, select FLOAT in the Put-away Template Code field. Create stockkeeping units for the item. On the stockkeeping unit card for location MAIN, enter FIXED in the Put-away Template Code field. On the stockkeeping unit card for WEST, leave the Put-away Template Code field blank.

<i class='far fa-square'></i> &nbsp;&nbsp;On the Bin Policies FastTab for both locations, select FIXED in the Put-away Template Code field. On the item, enter FLOAT in the Put-away Template Code field.

<i class='far fa-square'></i> &nbsp;&nbsp;On the Bin Policies FastTab for both locations, select FLOAT in the Put-away Template Code field. On the item, enter FIXED in the Put-away Template Code field.
<br />
<br />
<br />

####  2. On the put-away template card, you can select the Find Bin w. Less Than Min. Qty option. Where can you enter the minimum quantity that the program considers when putting items away?


<i class='far fa-square'></i> &nbsp;&nbsp;In the Reorder Point field on an item card or stockkeeping unit card

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In the Min. Qty. field on the Bin Content page

<i class='far fa-square'></i> &nbsp;&nbsp;In the Minimum Order Quantity field on the item card or stockkeeping unit card

<i class='far fa-square'></i> &nbsp;&nbsp;In the Maximum Weight field on the bin
<br />
<br />
<br />
