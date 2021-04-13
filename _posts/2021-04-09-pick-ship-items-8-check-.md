---
    layout: post
    title: Pick and ship items in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/pick-ship-items/8-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/pick-ship-items.svg">
####  1. What is the difference between an inventory pick and a warehouse pick?


<i class='far fa-square'></i> &nbsp;&nbsp;With an inventory pick, you can only handle inventory items, while with a warehouse pick, you can also handle service items.

<i class='far fa-square'></i> &nbsp;&nbsp;A warehouse pick can only be used for locations with the Directed Put-away and pick field enabled. An inventory pick can also be used for locations that do not use directed put-away and pick.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;An inventory pick is created for a sales order. A warehouse pick is created for a warehouse shipment.

<i class='far fa-square'></i> &nbsp;&nbsp;An inventory pick can handle multiple source documents at once. With a warehouse pick, you can only handle one order at a time.
<br />
<br />
<br />

####  2. The location that you are working in has required shipments and picks. What is the fastest way to send a sales order to the warehouse?


<i class='far fa-square'></i> &nbsp;&nbsp;Ask the warehouse worker to create a warehouse shipment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run the Create Warehouse Shipment function from the sales order document.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Create Inventory Pick function from the sales order document.

<i class='far fa-square'></i> &nbsp;&nbsp;Run the Create Warehouse Pick function from the sales order document.
<br />
<br />
<br />
