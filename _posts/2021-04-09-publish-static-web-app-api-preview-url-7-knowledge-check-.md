---
    layout: post
    title: Publish an API to Azure Static Web Apps 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/publish-static-web-app-api-preview-url/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/publish-static-web-app-api-preview-url.svg">
####  1. How do you customize the route endpoint for a function in an Azure Functions project?


<i class='far fa-square'></i> &nbsp;&nbsp;Rename index.js file to the name of the endpoint you desire.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Inside the function's function.json file, add a route property and set it to your desired endpoint path name.

<i class='far fa-square'></i> &nbsp;&nbsp;Endpoint paths cannot be customized.

<i class='far fa-square'></i> &nbsp;&nbsp;Name the function's symbol in the code to your desired name.
<br />
<br />
<br />

####  2. How do you deploy changes to your web app without affecting your production web site?


<i class='far fa-square'></i> &nbsp;&nbsp;Go to the production URL of your app.

<i class='far fa-square'></i> &nbsp;&nbsp;Go to your resource in the Azure portal and view the configuration.

<i class='far fa-square'></i> &nbsp;&nbsp;Push your commits to your watched branched of your git repository.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a preview URL by creating a pull request against the branch that your GitHub Action is watching.
<br />
<br />
<br />

####  3. How do you tell Azure Static Web Apps that you changed where your API is located?


<i class='far fa-square'></i> &nbsp;&nbsp;In the package.json file.

<i class='far fa-square'></i> &nbsp;&nbsp;Add an entry in routes.json for the location.

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Static Web Apps automatically knows where your code and API are located, without any configuration.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In the GitHub Actions workflow file in your .github/workflows folder.
<br />
<br />
<br />
