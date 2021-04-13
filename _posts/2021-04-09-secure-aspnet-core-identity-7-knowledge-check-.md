---
    layout: post
    title: Secure an ASP.NET Core web app with the Identity framework 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/secure-aspnet-core-identity/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/aspnetcore/secure-aspnet-core-identity.svg">
####  1. Suppose you want to add an IsEmployee claim to the authenticated user. By default, where is that claim persisted?


<i class='far fa-square'></i> &nbsp;&nbsp;All user claims are stored in the AspNetUsers table.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;All user claims are stored in the AspNetUserClaims table.

<i class='far fa-square'></i> &nbsp;&nbsp;All user claims are persisted in memory using session state.
<br />
<br />
<br />

####  2. Which of the following options is a Microsoft-supported data store for Identity with EF Core?


<i class='far fa-square'></i> &nbsp;&nbsp;SQL Server

<i class='far fa-square'></i> &nbsp;&nbsp;SQLite

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;SQL Server and SQLite
<br />
<br />
<br />

####  3. Identity creates a cookie named .AspNetCore.Identity.Application to preserve a user session. By default, when is the cookie created and when is it deleted?


<i class='far fa-square'></i> &nbsp;&nbsp;The cookie is created when the user navigates to the login page. The cookie is destroyed when the browser is closed.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The cookie is created after successfully authenticating on the login page. The cookie is destroyed when the Logout link is clicked.

<i class='far fa-square'></i> &nbsp;&nbsp;The cookie is created when the user navigates to the login page. The cookie is destroyed when the Logout link is clicked.
<br />
<br />
<br />
