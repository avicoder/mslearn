---
    layout: post
    title: Manage public folders in hybrid and cloud enterprise environments - Summary and knowledge check
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/m365-messaging-public-folders/summary-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/manage-public-folders.svg">
####  1. What are the two kinds of public folder hierarchies? One is read-write and the other is read-only.


<i class='far fa-square'></i> &nbsp;&nbsp;Legacy and modern.

<i class='far fa-square'></i> &nbsp;&nbsp;Top-level and sub-level.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Primary and secondary
<br />
<br />
<br />

####  2. How do you change the email address associated with a mail-enabled public folder?


<i class='far fa-square'></i> &nbsp;&nbsp;Using the EAC, change the email address on the summary screen, as you create a public folder.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Using the EAC, edit the properties in the email address section, after you've mail-enabled the public folder.

<i class='far fa-square'></i> &nbsp;&nbsp;Using the PowerShell command, Enable-MailPublicFolder, when you create a public folder.
<br />
<br />
<br />

####  3. What is the last step you should take when you move content between public folder mailboxes?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can only have one move request at a time, so you need to run the Remove-PublicFolderMoveRequest PowerShell command to delete the completed request.

<i class='far fa-square'></i> &nbsp;&nbsp;You aren't notified when a move request completes. You need to run the Get-PublicFolderMoveRequest PowerShell command to check the status of the request.

<i class='far fa-square'></i> &nbsp;&nbsp;After the move request has completed, you need to manually delete the original contents so there are no duplicates.
<br />
<br />
<br />

####  4. Which role allows you to export eDiscovery case data?


<i class='far fa-square'></i> &nbsp;&nbsp;eDiscovery Manager

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;eDiscovery Administrator

<i class='far fa-square'></i> &nbsp;&nbsp;eDiscovery Exporter
<br />
<br />
<br />

####  5. What is the guidance for using PST files to migrate public folders?


<i class='far fa-square'></i> &nbsp;&nbsp;The simplest way is to use PST files in most situations, and end users can complete them.

<i class='far fa-square'></i> &nbsp;&nbsp;You should never use PST files, as they can't migrate existing permissions and might cause mailbox size issues.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can use PST files, as they are a quick way to migrate a public folder.
<br />
<br />
<br />
