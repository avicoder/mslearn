---
    layout: post
    title: Understand how to use packages, variables, and functions in Go 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/go-variables-functions-packages/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/go/go-variables-functions-packages.svg">
####  1. How do you declare and initialize a variable?


<i class='far fa-square'></i> &nbsp;&nbsp;var firstName string

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;firstName := "John"

<i class='far fa-square'></i> &nbsp;&nbsp;string firstName = "John"

<i class='far fa-square'></i> &nbsp;&nbsp;firstName = "John"
<br />
<br />
<br />

####  2. What happens when you declare a variable but don't use it?


<i class='far fa-square'></i> &nbsp;&nbsp;You get a warning.

<i class='far fa-square'></i> &nbsp;&nbsp;Nothing. There's no problem if you have unused objects.

<i class='far fa-square'></i> &nbsp;&nbsp;You get a warning, but the next time the code won't compile.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You get an error. The program won't compile.
<br />
<br />
<br />

####  3. How do data conversion types work in Go?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You have to do conversion explicitly. Implicit conversion doesn't work in Go.

<i class='far fa-square'></i> &nbsp;&nbsp;You can do implicit casting from int to int32.

<i class='far fa-square'></i> &nbsp;&nbsp;You can only do it through external libraries.

<i class='far fa-square'></i> &nbsp;&nbsp;You can't convert from int to string or vice-versa.
<br />
<br />
<br />

####  4. Why would you use pointers in Go?


<i class='far fa-square'></i> &nbsp;&nbsp;Go doesn't support pointers.

<i class='far fa-square'></i> &nbsp;&nbsp;To free up memory.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To change variable values from the function caller.
<br />
<br />
<br />

####  5. How do you differentiate between a package and a standalone application?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A standalone application uses the package main. A package (library) uses a different name.

<i class='far fa-square'></i> &nbsp;&nbsp;You have to run either go create library or go create program.

<i class='far fa-square'></i> &nbsp;&nbsp;It doesn't matter. It depends on how you use the code after you're done programming.
<br />
<br />
<br />
