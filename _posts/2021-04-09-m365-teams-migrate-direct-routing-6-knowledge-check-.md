---
    layout: post
    title: Migrate to Direct Routing in Teams 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/m365-teams-migrate-direct-routing/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/migrate-to-direct-routing-in-teams.svg">
####  1. Which of the following should you consider about the user's phone number when making the cut over?


<i class='far fa-square'></i> &nbsp;&nbsp;Ensure that numbers now include the country dial code; for example, +1 for the US.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Ensure that it's no longer routed to the old system.

<i class='far fa-square'></i> &nbsp;&nbsp;Ensure that the new SIP attribute has been added to the phone number.
<br />
<br />
<br />

####  2. After running Get-CsOnlineUser, you see that OnPremHostingProvider, which was SRV, is now sipfed.online.lync.com. Which of the following describes the meaning of this change?


<i class='far fa-square'></i> &nbsp;&nbsp;Calls to this user will now go to Skype for Business.

<i class='far fa-square'></i> &nbsp;&nbsp;Calls to this user now bypass the SBC.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Direct routing is now enabled for the user.
<br />
<br />
<br />

####  3. Which of the following describes how to configure the SBC for dynamic routing?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Via an LDAP connection to the domain controller.

<i class='far fa-square'></i> &nbsp;&nbsp;Dynamic routing is enabled on the SBC through PowerShell.

<i class='far fa-square'></i> &nbsp;&nbsp;By querying the list of users in Teams.
<br />
<br />
<br />

####  4. Your Skype for Business environment has been decommissioned. A user tells you that their phone number has changed. After running the PowerShell command Get-CsOnlineUser for that user, you find OnPremLineURIManuallySet=False. Which of the following describes how you'll update the user's phone number?


<i class='far fa-square'></i> &nbsp;&nbsp;Through Active Directory Users and Groups.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Set-CsUser user -OnPremLineURI value.

<i class='far fa-square'></i> &nbsp;&nbsp;Edit the number in the SBC.
<br />
<br />
<br />
