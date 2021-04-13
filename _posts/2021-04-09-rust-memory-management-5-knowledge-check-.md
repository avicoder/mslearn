---
    layout: post
    title: Understand how Rust manages memory 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/rust-memory-management/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/rust-memory-management.svg">
####  1. What is the meaning of the <'a> segment in the struct declaration struct Nominee<'a> { person: &'a Person }?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It means that the Nominee struct will live no longer than the Person value that it borrows from.

<i class='far fa-square'></i> &nbsp;&nbsp;It means that the Nominee struct will live no longer than the AwardKind value that it borrows from.

<i class='far fa-square'></i> &nbsp;&nbsp;It means that the Nominee struct will live no longer than the String value that it holds.

<i class='far fa-square'></i> &nbsp;&nbsp;It means that the Nominee struct can have an optional value in its person field.
<br />
<br />
<br />

####  2. What type of aliasing is permitted in Rust?


<i class='far fa-square'></i> &nbsp;&nbsp;One mutable reference and multiple immutable references.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;One mutable reference or multiple immutable references.

<i class='far fa-square'></i> &nbsp;&nbsp;Many mutable references and no immutable references.

<i class='far fa-square'></i> &nbsp;&nbsp;Many mutable and immutable references.
<br />
<br />
<br />
