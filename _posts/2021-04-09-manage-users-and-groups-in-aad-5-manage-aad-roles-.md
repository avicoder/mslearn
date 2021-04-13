---
    layout: post
    title: Manage users and groups in Azure Active Directory - Use roles to control resource access
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/manage-users-and-groups-in-aad/5-manage-aad-roles/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/manage-users-and-groups-in-aad.svg">
####  1. What information does an Action provide in a role definition?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;An Action provides the allowed management capabilities for the role.

<i class='far fa-square'></i> &nbsp;&nbsp;An Action determines what data the role can manipulate.

<i class='far fa-square'></i> &nbsp;&nbsp;An Action decides what resource the role is applied to.
<br />
<br />
<br />

####  2. Which of the following sets the scope of a role to be the resource group myResourceGroup?


<i class='far fa-square'></i> &nbsp;&nbsp;/subscriptions/de324015-0284-4582-9d9c-6f1e52a30471

<i class='far fa-square'></i> &nbsp;&nbsp;/subscriptions/{ef67bd4f-d0f2-4845-b6dd-6cba225b4f10}/resourceGroups/myResourceGroup/backupvm1

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;/subscriptions/{ef67bd4f-d0f2-4845-b6dd-6cba225b4f10}/resourceGroups/myResourceGroup
<br />
<br />
<br />

####  3. How are NotActions used in a role definition?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;NotActions are subtracted from the Actions to define the list of permissible operations.

<i class='far fa-square'></i> &nbsp;&nbsp;NotActions are consulted after Actions to deny access to a specific operation.

<i class='far fa-square'></i> &nbsp;&nbsp;NotActions allow you to specify a single operation that is not allowed.
<br />
<br />
<br />
