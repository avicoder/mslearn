---
    layout: post
    title: Use methods and interfaces in Go 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/go-methods-interfaces/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/go/go-methods-interfaces.svg">
####  1. Function parameters are passed by value. How can you create a method that allows you to modify any field from the receiver?


<i class='far fa-square'></i> &nbsp;&nbsp;You have to return a value and then modify the object with the new value.

<i class='far fa-square'></i> &nbsp;&nbsp;You can't. Methods are read-only.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You have to use a pointer in the receiver when you want to modify any field from the receiver.

<i class='far fa-square'></i> &nbsp;&nbsp;You can't. Go can pass parameters by value only.
<br />
<br />
<br />

####  2. Is it possible to create methods for native types such as string?


<i class='far fa-square'></i> &nbsp;&nbsp;No, you'll have a compile error if you try to do it.

<i class='far fa-square'></i> &nbsp;&nbsp;Yes, but you can create methods only for string or int.

<i class='far fa-square'></i> &nbsp;&nbsp;No, you can create only methods for structs.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes, but you have to create a custom type wrapper.
<br />
<br />
<br />

####  3. Are interfaces in Go explicit or implicit?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Interfaces in Go are implicit. There's no keyword such as implements or symbols such as : to explicitly implement an interface.

<i class='far fa-square'></i> &nbsp;&nbsp;Interfaces in Go are explicit. You have to use the : symbol.

<i class='far fa-square'></i> &nbsp;&nbsp;Interfaces in Go are implicit, but you can implement interfaces only from the current package, not from other packages.
<br />
<br />
<br />
