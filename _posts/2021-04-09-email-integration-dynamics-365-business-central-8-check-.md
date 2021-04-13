---
    layout: post
    title: Integrate Business Central with email and Outlook  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/email-integration-dynamics-365-business-central/8-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/email-integration-dynamics-365-business-central.svg">
####  1. How can you set up Dynamics 365 Business Central as your Business Inbox in Outlook?


<i class='far fa-square'></i> &nbsp;&nbsp;In the Microsoft 365 admin center, for each user that should be able to use Business Central in Outlook, select the Use Microsoft Dynamics 365 Business Central in Outlook field.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;In Business Central, one of the steps in the Getting Started assisted setup is Run your business within Microsoft 365 window. In that window, when you choose the Set up in Outlook button, you must specify your Microsoft 365 username and password. The Business Central add-ins are then automatically added to your Outlook.

<i class='far fa-square'></i> &nbsp;&nbsp;In Outlook, you need to go to the add-ins page. There you can look for download and activate the Business Central add-inn. The Business Central add-ins are then added to your Outlook.

<i class='far fa-square'></i> &nbsp;&nbsp;At this moment, Business Central cannot be used as your Business Inbox in Outlook.
<br />
<br />
<br />

####  2. How can you set up your system so that emails can be sent from within Business Central?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To send and receive emails from within Business Central, you must fill in the fields in the SMTP Mail Setup window. You can either set email up manually or you can get help by using the Email Setup assisted setup.

<i class='far fa-square'></i> &nbsp;&nbsp;In the User Setup page, enter the email address of each users, and then select the field “Connect with Outlook”. The next time a user logs in to Business Central, the program automatically connects with Outlook.

<i class='far fa-square'></i> &nbsp;&nbsp;In the current release of the product it is not possible to send any emails from within the application. This functionality will become available in a future release.

<i class='far fa-square'></i> &nbsp;&nbsp;To enable this feature, you need to use the development environment and set the Enable email for Business Central to true.
<br />
<br />
<br />
