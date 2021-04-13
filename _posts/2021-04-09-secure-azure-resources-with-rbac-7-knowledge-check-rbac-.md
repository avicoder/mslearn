---
    layout: post
    title: Secure your Azure resources with Azure role-based access control (Azure RBAC)  - Using Azure RBAC
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/secure-azure-resources-with-rbac/7-knowledge-check-rbac/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/secure-azure-resources-with-rbac.svg">
####  1. Suppose a team member can't view resources in a resource group. Where would the administrator go to check the team member's access?


<i class='far fa-square'></i> &nbsp;&nbsp;Check the team member's permissions by going to their Azure profile > My permissions.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Go to the resource group and select Access control (IAM) > Role assignments.

<i class='far fa-square'></i> &nbsp;&nbsp;Go to one of the resources in the resource group and select Role assignments.
<br />
<br />
<br />

####  2. Suppose an administrator in another department needs access to a virtual machine managed by your department. What's the best way to grant them access to just that resource?


<i class='far fa-square'></i> &nbsp;&nbsp;At the resource scope, create a role for them with the appropriate access.

<i class='far fa-square'></i> &nbsp;&nbsp;At the resource group scope, assign the role with the appropriate access.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;At the resource scope, assign the role with the appropriate access.
<br />
<br />
<br />

####  3. Suppose a developer needs full access to a resource group. If you are following least-privilege best practices, what scope should you specify?


<i class='far fa-square'></i> &nbsp;&nbsp;Resource

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Resource group

<i class='far fa-square'></i> &nbsp;&nbsp;Subscription
<br />
<br />
<br />

####  4. Suppose an administrator needs to generate a report of the role assignments for the last week. Where in the Azure portal would they generate that report?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Search for Activity log and filter on the Create role assignment (roleAssignments) operation.

<i class='far fa-square'></i> &nbsp;&nbsp;At the appropriate scope, go to Access control (IAM) > Download role assignments.

<i class='far fa-square'></i> &nbsp;&nbsp;At the appropriate scope, go to Access control (IAM) > Role assignments.
<br />
<br />
<br />
