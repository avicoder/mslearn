---
    layout: post
    title: Configure policy templates for custom connectors in Power Automate  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/policy-templates-custom-connectors/7-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/policy-templates-custom-connectors.svg">
####  1. A policy template is being applied to a custom connector action that you don't want it to run for. What should you do to fix the problem?


<i class='far fa-square'></i> &nbsp;&nbsp;Edit the action definition and turn off the policy template.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Edit the policy template and ensure that the required triggers and actions are explicitly selected and the one that you don’t want to run isn't selected.

<i class='far fa-square'></i> &nbsp;&nbsp;Edit the policy template and make sure that no triggers and actions are specified.

<i class='far fa-square'></i> &nbsp;&nbsp;Edit the Excluded Actions property of the custom connector and make sure that the target action is selected.
<br />
<br />
<br />

####  2. You want to allow makers to configure the host name by providing the URL on the connection dialog box when they instantiate a connection by using your custom connector. What do you need to configure?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure a Route Request policy template.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the User Prompt property of the Set Host URL policy template to Yes.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You must add a connection property and configure a Set Host URL policy template.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a Set Property policy template.
<br />
<br />
<br />

####  3. The API that you're using returns categories in a single string field (for example, Categories A,B,C,D). Instead, you want it to be an array. What policy template would you configure?


<i class='far fa-square'></i> &nbsp;&nbsp;Configure a Convert object to an array policy template.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Configure a Convert delimited string into an array of objects policy template.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a Convert array to an object policy template.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a Split string policy template.
<br />
<br />
<br />
