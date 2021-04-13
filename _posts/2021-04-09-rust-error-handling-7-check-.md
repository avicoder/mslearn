---
    layout: post
    title: Handle errors in Rust 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/rust-error-handling/7-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/rust-error-handling.svg">
####  1. Which of the following attempts will not cause a Rust program to panic?


<i class='far fa-square'></i> &nbsp;&nbsp;Accessing an out-of-bounds index of a vector with vector[index] notation.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Accessing an out-of-bounds index of a vector with vector.get(index) notation.

<i class='far fa-square'></i> &nbsp;&nbsp;Accessing an out-of-bounds index of an array with array[index] notation.

<i class='far fa-square'></i> &nbsp;&nbsp;Accessing a non-existent key of a hash map with HashMap[key] notation.
<br />
<br />
<br />

####  2. How can you represent the possibility of absence of a value of a given type, T, in Rust?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The Option<T> type.

<i class='far fa-square'></i> &nbsp;&nbsp;The Result<T, bool> type.

<i class='far fa-square'></i> &nbsp;&nbsp;A false value of the bool type.

<i class='far fa-square'></i> &nbsp;&nbsp;An empty tuple: ().
<br />
<br />
<br />

####  3. How can you represent the possibility of input/output (I/O) failure when you're obtaining a value of a given type, T?


<i class='far fa-square'></i> &nbsp;&nbsp;The Option<T> type.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The Result<T, io::Error> type.

<i class='far fa-square'></i> &nbsp;&nbsp;An empty Vec<T>.

<i class='far fa-square'></i> &nbsp;&nbsp;An empty tuple: ().
<br />
<br />
<br />
