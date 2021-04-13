---
    layout: post
    title: Understand Conditional Access policies using Microsoft Endpoint Manager 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/policy-security-management-using-microsoft-endpoint-manager/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/policy-security-management-using-microsoft-endpoint-manager.svg">
####  1. What is Conditional Access?


<i class='far fa-square'></i> &nbsp;&nbsp;Conditional Access allows anonymous users to access organizational resources on trusted devices.

<i class='far fa-square'></i> &nbsp;&nbsp;Conditional Access prevents trusted users from accessing trusted devices and trusted apps.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Conditional Access ensures that only trusted users can access organizational resources on trusted devices using trusted apps.
<br />
<br />
<br />

####  2. When assign a policy, what is the difference between using an assigned group and using a dynamic group?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;An assigned group is a group of users or devices that you manually add into a static group. A dynamic group is a group of users or devices that are automatically assigned based on an expression you create. In addition, dynamic groups requires Azure AD Premium.

<i class='far fa-square'></i> &nbsp;&nbsp;An assigned group is a group of users or devices that automatically set. A dynamic group is a group of users that you manually set.

<i class='far fa-square'></i> &nbsp;&nbsp;For policies, there are no differences when assigning based on assigned group or dynamic group.
<br />
<br />
<br />

####  3. When would you assign a policy to a device group?


<i class='far fa-square'></i> &nbsp;&nbsp;Assign a policy to a device group when you want to have different policy settings for each user.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;If you want to apply policy settings on a device, regardless of who's signed in, then assign your policies to a devices group.

<i class='far fa-square'></i> &nbsp;&nbsp;If you don't want to have any policy settings for the device, use a device group.
<br />
<br />
<br />

####  4. It is possible to integrate Microsoft Defender ATP with Intune, but is it possible to integrate Microsoft Defender ATP with Configuration Manager?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes. Using tenant attach in a co-managed endpoint management scenario, you can integrate Configuration Manager with Microsoft Defender ATP to gain access to security tasks that help enterprises detect, investigate, and respond to advanced attacks on their networks.

<i class='far fa-square'></i> &nbsp;&nbsp;No. You can only integrate Microsoft Defender ATP with Intune.
<br />
<br />
<br />
