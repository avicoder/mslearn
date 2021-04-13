---
    layout: post
    title: Choose a data storage approach in Azure - Group multiple operations in a transaction
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/choose-storage-approach-in-azure/4-transactions/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/choose-storage-approach-in-azure.svg">
####  1. Which type of transactional database system would work best for product data?


<i class='far fa-square'></i> &nbsp;&nbsp;OLAP

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;OLTP
<br />
<br />
<br />

####  2. Suppose the operations to update inventory and process payments are in the same transaction. A user is attempting to apply a $30 store credit for the full amount of an order, and submitted the exact same order using the store credit (for the full amount) using their phone and laptop at the same time - so two identical orders are received. The database behind the scenes is an ACID-compliant database, what would happen?


<i class='far fa-square'></i> &nbsp;&nbsp;Both orders would be processed and use the in-store credit.

<i class='far fa-square'></i> &nbsp;&nbsp;One order would be processed and use the in-store credit, and the other order would update the remaining inventory for the items in the basket, but would not complete the order.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;One order would be processed and use the in-store credit, and the other order would not be processed.
<br />
<br />
<br />
