---
    layout: post
    title: Create a web API with ASP.NET Core 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/build-web-api-aspnet-core/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/build-web-api-net-core.svg">
####  1. Suppose you need to update a product's name. Which HTTP action verb is the best fit for this request?


<i class='far fa-square'></i> &nbsp;&nbsp;POST

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;PUT

<i class='far fa-square'></i> &nbsp;&nbsp;DELETE
<br />
<br />
<br />

####  2. Suppose you have successfully created a product via the POST verb. The response contains a location header. What's the purpose of that location header?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To identify the location of the new resource that was created by the request.

<i class='far fa-square'></i> &nbsp;&nbsp;To provide the client with a URL for the POST action.

<i class='far fa-square'></i> &nbsp;&nbsp;To identify an existing product with the same name.
<br />
<br />
<br />

####  3. In which scenario is it most appropriate to return an HTTP 404 status code, and how is it accomplished in ASP.NET Core?


<i class='far fa-square'></i> &nbsp;&nbsp;The product was successfully updated in the database. Call the BadRequest method to generate a 404.

<i class='far fa-square'></i> &nbsp;&nbsp;When model validation fails because the action's required parameters are missing. Call the BadRequest method to generate a 404.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;When you've requested a product by ID and a match doesn't exist in the underlying data store. Call the NotFound method to generate a 404.
<br />
<br />
<br />
