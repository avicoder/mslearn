---
    layout: post
    title: Manage complex cloud deployments by using advanced ARM template features 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/manage-deployments-advanced-arm-template-features/10-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/manage-deployments-advanced-arm-template-features.svg">
####  1. How do you create a dependency between two or more resources?


<i class='far fa-square'></i> &nbsp;&nbsp;Create a resources attribute on the parent resource. Add the child resource as a value of the resources attribute you created.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a dependencies attribute on the dependent resource. Add the resource you depend on as a value to the dependencies attribute.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add a dependsOn construct on a resource, and add the name or ID of the resource it depends on.
<br />
<br />
<br />

####  2. The condition element is used to:


<i class='far fa-square'></i> &nbsp;&nbsp;Conditionally set values on a resource's attribute.

<i class='far fa-square'></i> &nbsp;&nbsp;Conditionally run shell commands in your ARM template.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Conditionally deploy a resource.
<br />
<br />
<br />

####  3. How do you get the current index in a copy iteration?


<i class='far fa-square'></i> &nbsp;&nbsp;Refer to the $index field within the copy element.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You use the copyIndex() function.

<i class='far fa-square'></i> &nbsp;&nbsp;There's a currentIndex() function that returns the current index value.
<br />
<br />
<br />
