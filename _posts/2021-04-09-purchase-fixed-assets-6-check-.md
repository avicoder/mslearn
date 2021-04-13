---
    layout: post
    title: Purchase fixed assets in Dynamics 365 Business Central  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/purchase-fixed-assets/6-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/purchase-fixed-assets.svg">
####  1. Can you post an additional acquisition cost to an asset for which you already calculated depreciation?


<i class='far fa-square'></i> &nbsp;&nbsp;No, you must create a new asset to which you can post the additional acquisition cost and group the assets as main assets and asset components.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes, you can post additional acquisition costs the same way that you would post the original acquisition cost from a purchase invoice, the FA GL journal, or the FA journal.

<i class='far fa-square'></i> &nbsp;&nbsp;Yes, with the fixed asset reclassification journal, you can post 100 percent of the additional acquisition cost to the asset with the original acquisition cost.

<i class='far fa-square'></i> &nbsp;&nbsp;Yes, but only if the Allow Additional Acquisition Costs field on the asset’s depreciation book is selected.
<br />
<br />
<br />

####  2. What happens if you post the acquisition cost to an asset with a purchase line that has the Use Duplication List field selected?


<i class='far fa-square'></i> &nbsp;&nbsp;Business Central posts the acquisition cost to all depreciation books of the asset for which the Part of Duplication List option is selected.

<i class='far fa-square'></i> &nbsp;&nbsp;Business Central automatically posts the acquisition cost to all depreciation books of the asset.

<i class='far fa-square'></i> &nbsp;&nbsp;Business Central creates a new purchase invoice for the other depreciation books.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Business Central will duplicate the journal line to a separate journal from which it will be posted for each depreciation book that is a part of a duplication list.
<br />
<br />
<br />
