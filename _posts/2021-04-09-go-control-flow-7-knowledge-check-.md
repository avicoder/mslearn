---
    layout: post
    title: Use control flows in Go 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/go-control-flow/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/go/go-control-flow.svg">
####  1. Can variables that are declared within an if statement be used outside the if statement?


<i class='far fa-square'></i> &nbsp;&nbsp;Yes, because variables have a global scope.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No, the variable scope is only within the if block or nested if statements.

<i class='far fa-square'></i> &nbsp;&nbsp;Yes, as long as they're used within the function.

<i class='far fa-square'></i> &nbsp;&nbsp;No, a variable must be declared outside an if statement.
<br />
<br />
<br />

####  2. In a switch block, does a break keyword need to be included at the end of every case statement?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No, Go doesn't require you to include the break keyword.

<i class='far fa-square'></i> &nbsp;&nbsp;Yes, otherwise the following case statements will be evaluated.

<i class='far fa-square'></i> &nbsp;&nbsp;No, Go doesn't support the break keyword.
<br />
<br />
<br />

####  3. What does the panic() function do in Go?


<i class='far fa-square'></i> &nbsp;&nbsp;It throws an error that you need to catch. Otherwise, the program crashes without any error.

<i class='far fa-square'></i> &nbsp;&nbsp;It prints a panic message to the console.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It crashes a program and prints the error message and its stack trace.
<br />
<br />
<br />
