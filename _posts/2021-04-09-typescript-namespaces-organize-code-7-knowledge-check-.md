---
    layout: post
    title: Organize code using TypeScript namespaces 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/typescript-namespaces-organize-code/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/typescript/typescript-namespaces-organize-code.svg">
####  1. What happens when you add code to a namespace?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Declarations are removed from the global namespace.

<i class='far fa-square'></i> &nbsp;&nbsp;Declarations are removed from the global namespace only if the namespace is in a separate file.

<i class='far fa-square'></i> &nbsp;&nbsp;Declarations contribute to 'global scope pollution'.
<br />
<br />
<br />

####  2. How do you make a component available outside the scope of a namespace?


<i class='far fa-square'></i> &nbsp;&nbsp;Add the import keyword to the file that will use the component.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add the export keyword to the declaration.

<i class='far fa-square'></i> &nbsp;&nbsp;Add a reference statement to the file that will use the component.
<br />
<br />
<br />

####  3. What is the option that tells the TypeScript compiler to output multiple files using and containing namespaces into a single JavaScript file?


<i class='far fa-square'></i> &nbsp;&nbsp;--multifile

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;--outfile

<i class='far fa-square'></i> &nbsp;&nbsp;No option is required. The Typescript compiler does this operation by default.
<br />
<br />
<br />
