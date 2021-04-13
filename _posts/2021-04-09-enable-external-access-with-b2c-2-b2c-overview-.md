---
    layout: post
    title: Enable secure access to apps for external users with Azure AD B2C - What is Azure AD B2C?
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/enable-external-access-with-b2c/2-b2c-overview/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/enable-external-access-with-b2c.svg">
####  1. Why is a B2C tenant needed for you to use Azure AD B2C?


<i class='far fa-square'></i> &nbsp;&nbsp;Because a B2C tenant is a logical representation of your internal users and the applications they use.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Because a B2C tenant is a logical representation of your customers and the applications they use.

<i class='far fa-square'></i> &nbsp;&nbsp;Because a tenant is a physical representation of your users and the applications they use.
<br />
<br />
<br />

####  2. Patients must be able to access the health application by using their LinkedIn, Twitter, and Facebook accounts. How can you support that in your app?


<i class='far fa-square'></i> &nbsp;&nbsp;You can configure social identity providers. But, for a single application, only one social account type can be used at a time.

<i class='far fa-square'></i> &nbsp;&nbsp;Social identity accounts can't be used with Azure AD B2C. Only accounts that you manage can be used to access the application.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Select the social identity providers for these types of social accounts, and then configure them appropriately.
<br />
<br />
<br />

####  3. You want to collect the patient's job title, if they have one, when they sign up for your application. How do you do that?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Configure a user flow and set it to collect a job-title attribute.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a social identity provider and set it to collect a job title attribute.

<i class='far fa-square'></i> &nbsp;&nbsp;Configure a custom page-layout template and put a text box in it to collect job titles.
<br />
<br />
<br />
