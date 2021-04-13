---
    layout: post
    title: Implement generic types and traits 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/rust-generic-types-traits/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/rust-generic-types-traits.svg">
####  1. When are Rust traits useful?


<i class='far fa-square'></i> &nbsp;&nbsp;When a function or struct needs to accept optional parameters.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When we need to specify function or struct parameters in terms of behavior instead of concrete value.

<i class='far fa-square'></i> &nbsp;&nbsp;When we need to avoid the compile time guarantees of the Borrow Checker.

<i class='far fa-square'></i> &nbsp;&nbsp;When we need our values to continue valid even past their lifetime scope.
<br />
<br />
<br />

####  2. What does the following function signature mean? fn show_on_screen<T: Display>(data: T)


<i class='far fa-square'></i> &nbsp;&nbsp;The data parameter can be of any type.

<i class='far fa-square'></i> &nbsp;&nbsp;The data parameter can be of any type that optionally implements the Display trait.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The data parameter is restricted only to types that implement the Display trait.

<i class='far fa-square'></i> &nbsp;&nbsp;The data parameter is optional.
<br />
<br />
<br />
