---
    layout: post
    title: Create Power Automate OpenAPI custom connectors  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/custom-connectors-open-api/6-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/custom-connectors-open-api.svg">
####  1. You've implemented a custom connector that uses API Key authentication. You want to have it validate the key at connection creation time. What should you do to implement this action?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Configure an OpenAPI extension x-ms-capabilities with the testConnection property configured.

<i class='far fa-square'></i> &nbsp;&nbsp;Use a policy template to set the key in the header.

<i class='far fa-square'></i> &nbsp;&nbsp;Enable the test connection feature in the custom connector designer.

<i class='far fa-square'></i> &nbsp;&nbsp;Include {KEY} placeholder as the key value and the connection designer will replace it with a valid key when creating a connection.
<br />
<br />
<br />

####  2. The parameters on one of your custom connector actions vary based on the selected category parameter value. You want users to only see parameters that are valid for a specific category. What should you do to implement this specification?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a policy template.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Configure a Dynamic Schema OpenAPI extension.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a Dynamic Values OpenAPI extension.

<i class='far fa-square'></i> &nbsp;&nbsp;Use Swagger editor to enter the list of valid parameters that are sorted by category according to OpenAPI specifications.
<br />
<br />
<br />

####  3. You want to configure Dynamic Values for a parameter on your custom connector action. What support do you need from the API to allow you to complete this configuration?


<i class='far fa-square'></i> &nbsp;&nbsp;API needs to be compliant with OpenAPI specifications.

<i class='far fa-square'></i> &nbsp;&nbsp;API needs to include an operation that returns the schema for the parameter.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;API needs to include an operation that returns an array of valid values for that parameter.

<i class='far fa-square'></i> &nbsp;&nbsp;Nothing, dynamic values only work with an array of values that are specified in the OpenAPI definition.
<br />
<br />
<br />

####  4. Which of the following is an alternative option to configure an OpenAPI extension if you don’t want to use the Swagger editor?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure the extension when you build a Power Automate flow.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the Power Platform command-line tool and the editor of your choice.

<i class='far fa-square'></i> &nbsp;&nbsp;Use Solution explorer to configure the extension.

<i class='far fa-square'></i> &nbsp;&nbsp;Swagger editor is the only available method of configuring an OpenAPI extension.
<br />
<br />
<br />
