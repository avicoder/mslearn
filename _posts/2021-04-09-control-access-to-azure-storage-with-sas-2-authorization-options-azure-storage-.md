---
    layout: post
    title: Control access to Azure Storage with shared access signatures - Authorization options for Azure Storage
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/control-access-to-azure-storage-with-sas/2-authorization-options-azure-storage/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/control-access-to-azure-storage-with-sas.svg">
####  1. Your organization has an internal system to share patient appointment information and notes. You can secure the access based on a user's membership in an Azure Active Directory (Azure AD) group. Which kind of authorization supports this scenario best, and why?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a shared access signature (SAS) token. You use the Azure AD credentials and a user delegation SAS token.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use Azure Active Directory. By using Azure AD, you can create a service principal to authenticate the app.

<i class='far fa-square'></i> &nbsp;&nbsp;Use a shared key. The Azure Storage account can create and revoke keys that will be used in your app.
<br />
<br />
<br />

####  2. Your public-facing static website stores all its public UI images in blob storage. The website needs to display the graphics without any kind of authorization. Which is the best option?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Public access

<i class='far fa-square'></i> &nbsp;&nbsp;Shared key

<i class='far fa-square'></i> &nbsp;&nbsp;Shared access signature
<br />
<br />
<br />
