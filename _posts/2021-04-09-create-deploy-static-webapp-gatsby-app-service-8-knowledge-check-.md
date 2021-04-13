---
    layout: post
    title: Create and publish a static web app with Gatsby and Azure Static Web Apps 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-deploy-static-webapp-gatsby-app-service/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/static-apps-gatsby.svg">
####  1. How would you create a page in a Gatsby app?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a React component in the pages directory.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a component anywhere in your project. Gatsby will scan the directory for React components.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a component with the Page prefix in its component name.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a Markdown file and place it in the pages directory.
<br />
<br />
<br />

####  2. How would you set up a default url for a page component?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You wouldn't. Gatsby does this for you.

<i class='far fa-square'></i> &nbsp;&nbsp;Set up the route by implementing the Gatsby API in the file gatsby-node.js.

<i class='far fa-square'></i> &nbsp;&nbsp;Create an App.js entry component and within it a Route component and resolver component for each route.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a React component in the pages directory and call the registerRoute() method, passing the route as a string together with the component.
<br />
<br />
<br />

####  3. How would you use data from the in-memory data graph in your page component?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Construct a page component and define a variable query that contains a GraphQL query. Then render the query response in the component.

<i class='far fa-square'></i> &nbsp;&nbsp;Do a fetch request and render the response in the component.

<i class='far fa-square'></i> &nbsp;&nbsp;Use Gatsby's Data component, set the query property to your query and render your Page component in its render property.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the function useData() and pass it your query as a parameter. It will return an object with a property data that contains your GraphQL response.
<br />
<br />
<br />

####  4. What pre-steps would you need to take to deploy a Gatsby app using the Azure Static Web Apps service?


<i class='far fa-square'></i> &nbsp;&nbsp;Commit changes to the Git repo, build the project, and push it to GitHub

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Commit changes to the Git repo and push it to GitHub

<i class='far fa-square'></i> &nbsp;&nbsp;Run gatsby build to create a deployable directory. Compress the resulting build directory into a tarball. The tarball can now be uploaded to Azure Static Web Apps service.

<i class='far fa-square'></i> &nbsp;&nbsp;Run gatsby deploy. This will create a binary that you can deploy to Azure Static Web Apps service.
<br />
<br />
<br />
