---
    layout: post
    title: Use data types and structs, arrays, slices, and maps in Go 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/go-data-types/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/go/go-data-types.svg">
####  1. Arrays are a fixed-length data type, but how can you define their size based on the data you used to initialize them?


<i class='far fa-square'></i> &nbsp;&nbsp;You have to determine the number of elements when declaring the array.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can use an ellipsis like this q := [...]int{1, 2, 3}.

<i class='far fa-square'></i> &nbsp;&nbsp;You have to create a slice to define their size.
<br />
<br />
<br />

####  2. A slice works with an underlying array, and arrays are fixed-sized length. What happens when you add an element to the slice and the underlying array is full?


<i class='far fa-square'></i> &nbsp;&nbsp;You get a panic error.

<i class='far fa-square'></i> &nbsp;&nbsp;You don't get an error, but the new element is not added to the slice.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Go doubles the size of the underlying array.
<br />
<br />
<br />

####  3. What happens when you create another slice using the slice operator s[i:j] and you make a change to an element in the new slice?


<i class='far fa-square'></i> &nbsp;&nbsp;Only the slice you created gets affected because when you make a sub slice it points to a new memory address.

<i class='far fa-square'></i> &nbsp;&nbsp;You can't create a sub slice, so you'd have to create a new one.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The original slice changes because a slice is simply a pointer to an underlying array.
<br />
<br />
<br />

####  4. When you're iterating the elements of a map, can you access the key and its value simultaneously?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You could use the syntax for key, value := range map. to access the key and value

<i class='far fa-square'></i> &nbsp;&nbsp;No, you can only access the map's values.

<i class='far fa-square'></i> &nbsp;&nbsp;You can only access both the key and the value when they are the same type.
<br />
<br />
<br />

####  5. Can you embed one struct into another struct?


<i class='far fa-square'></i> &nbsp;&nbsp;No, because Go doesn't have support for inheritance.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes, and you can even access the parent properties as if it was part of the child struct.

<i class='far fa-square'></i> &nbsp;&nbsp;No, you have to use two structs and repeat code as needed.
<br />
<br />
<br />
