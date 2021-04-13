---
    layout: post
    title: Introduction to object-oriented programming with Python 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/python-object-oriented-programming/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/student-evangelism/python-object-oriented-programming-badge.svg">
####  1. What is the difference between a class and an object?


<i class='far fa-square'></i> &nbsp;&nbsp;They're the same thing.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A class is a blueprint. An object is the concrete instance you build from the blueprint.

<i class='far fa-square'></i> &nbsp;&nbsp;A class has data and an object doesn't.

<i class='far fa-square'></i> &nbsp;&nbsp;A class has methods and an object doesn't.
<br />
<br />
<br />

####  2. How does Python implement accessors?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It uses prefixes. One underscore, _, at the beginning of the name indicates this variable is protected. Two underscores, __, make the variable private and will raise an exception if assigned.

<i class='far fa-square'></i> &nbsp;&nbsp;It uses the keywords private and public.

<i class='far fa-square'></i> &nbsp;&nbsp;Everything in a Python class is hidden by default and must be exposed by adding methods that return the variables' values.

<i class='far fa-square'></i> &nbsp;&nbsp;Add the decorator @public or @private to make something public or private.
<br />
<br />
<br />

####  3. Choose the best explanation that explains the keyword self.


<i class='far fa-square'></i> &nbsp;&nbsp;It's a keyword that refers to the object instance. You can also use the this keyword.

<i class='far fa-square'></i> &nbsp;&nbsp;The self keyword refers to the underlying class of the object.

<i class='far fa-square'></i> &nbsp;&nbsp;The only time the self keyword is used is to refer to members of the object, and it's passed as a parameter.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The self keyword refers to the object instance. Variables that are part of the object instance need to be assigned to self.  The self keyword is also passed to every method of a class that needs to access the object instance.
<br />
<br />
<br />
