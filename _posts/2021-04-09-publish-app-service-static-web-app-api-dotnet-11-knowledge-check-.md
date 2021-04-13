---
    layout: post
    title: Publish a Blazor WebAssembly app and .NET API with Azure Static Web Apps 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/publish-app-service-static-web-app-api-dotnet/11-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/publish-static-web-app-and-api-dotnet.svg">
####  1. When you make changes to your app, how do you publish an update to Azure Static Web Apps?


<i class='far fa-square'></i> &nbsp;&nbsp;Delete the Azure Static Web Apps instance and recreate it.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Push commits to the watched branched or create pull request to watched branch.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a new GitHub Actions workflow to build and publish your web app.

<i class='far fa-square'></i> &nbsp;&nbsp;Create and push a new branch to your git repository.
<br />
<br />
<br />

####  2. How do you view the progress of building and redeploying after you make changes to your app?


<i class='far fa-square'></i> &nbsp;&nbsp;Go to the production URL of your app.

<i class='far fa-square'></i> &nbsp;&nbsp;Go to your resource in the Azure portal and view the configuration.

<i class='far fa-square'></i> &nbsp;&nbsp;Push your commits to your watched branched of your git repository.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Go to the repository on github.com, then navigate to the Actions menu.
<br />
<br />
<br />

####  3. How do you configure your app so that when you navigate to /about in the browser, it serves the root index.html file?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add an entry in routes.json for a wildcard route /* to serve /index.html.

<i class='far fa-square'></i> &nbsp;&nbsp;Add an entry in Client.csproj for a wildcard route /* to serve /index.html.

<i class='far fa-square'></i> &nbsp;&nbsp;Add an entry in routes.json for a wildcard route /index to serve /index.html.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a wildcard route in the GitHub Actions workflow file to serve /index.html.
<br />
<br />
<br />

####  4. How do you tell Azure Static Web Apps that you changed where your API is located?


<i class='far fa-square'></i> &nbsp;&nbsp;In the Client.csproj file.

<i class='far fa-square'></i> &nbsp;&nbsp;Add an entry in routes.json for the location.

<i class='far fa-square'></i> &nbsp;&nbsp;Azure Static Web Apps automatically knows where your code and API are located, without any configuration.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In the GitHub Actions workflow file in your .github/workflows folder.
<br />
<br />
<br />
