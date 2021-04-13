---
    layout: post
    title: Customize a Xamarin.Forms ListView - Use multiple cell layouts in a ListView
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/customize-xamarin-forms-listview/3-use-multiple-cell-layouts-in-a-listview/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/xamarin/customize-xamarin-forms-listview-badge.svg">
####  1. What does a DataTemplateSelector allow you to do?


<i class='far fa-square'></i> &nbsp;&nbsp;Build DataTemplate instances in code.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Return a different DataTemplate depending on the row.

<i class='far fa-square'></i> &nbsp;&nbsp;Provide row selection handling in your DataTemplate.

<i class='far fa-square'></i> &nbsp;&nbsp;Load default cell styles automatically.
<br />
<br />
<br />

####  2. How many DataTemplate instances should a DataTemplateSelector create?


<i class='far fa-square'></i> &nbsp;&nbsp;One. Share an instance of DataTemplate and reset the CellType property when you return each record.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;One per cell type. Records with the same cell type should return the same DataTemplate instance.

<i class='far fa-square'></i> &nbsp;&nbsp;One per record. Instantiate and return a DataTemplate with the correct cell type.
<br />
<br />
<br />
