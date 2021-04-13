---
    layout: post
    title: Build Serverless APIs with Azure Functions 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-api-azure-functions/11-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/build-api-azure-functions.svg">
####  1. What do you need to do in an Azure Function to make it an HTTP endpoint?


<i class='far fa-square'></i> &nbsp;&nbsp;Name the main file 'index'.

<i class='far fa-square'></i> &nbsp;&nbsp;Add a CONNECTION_STRING property to the 'local.settings.json' file.

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Functions are accessible over HTTP by default.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Select the 'HTTP Trigger' template when creating a function.
<br />
<br />
<br />

####  2. What is the RESTful way to handle a delete product action in your API?


<i class='far fa-square'></i> &nbsp;&nbsp;Set the URL to /products, pass the ID of the item in the request body and use an HTTP DELETE method.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the URL to /products, pass in the ID of the item as a URL parameter (products/1) and set the HTTP method to POST.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the URL to /delete, pass in the ID of the item as a URL parameter (products/1) and set the HTTP method to DELETE.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set the URL to /products, pass in the ID of the item as a URL parameter (products/1) and set the HTTP method to DELETE.
<br />
<br />
<br />

####  3. How do you specify app settings for an Azure Functions project?


<i class='far fa-square'></i> &nbsp;&nbsp;In the package.json file.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Azure Functions will automatically read settings from a local.settings.json file.

<i class='far fa-square'></i> &nbsp;&nbsp;Specify them on the process.env object.

<i class='far fa-square'></i> &nbsp;&nbsp;In the env.development file
<br />
<br />
<br />
