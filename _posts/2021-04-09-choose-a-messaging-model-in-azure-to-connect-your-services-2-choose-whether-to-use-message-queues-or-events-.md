---
    layout: post
    title: Choose a messaging model in Azure to loosely connect your services - Choose whether to use messages or events
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/choose-a-messaging-model-in-azure-to-connect-your-services/2-choose-whether-to-use-message-queues-or-events/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/choose-a-messaging-model-in-azure-to-connect-your-services.svg">
####  1. Suppose you have a distributed application with a web service that authenticates users. When a user logs on, the web service notifies all the client applications so they can display that user's status as "Online". Is the login notification an example of a message or an event?


<i class='far fa-square'></i> &nbsp;&nbsp;Message

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Event
<br />
<br />
<br />

####  2. Suppose you have a distributed application with a web service that lets users manage their account. Users can sign up, edit their profile, and delete their account. When a user deletes their account, your web service notifies your data layer so the user's data will be removed from the database. Is the delete-account notification an example of a message or an event?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Message

<i class='far fa-square'></i> &nbsp;&nbsp;Event
<br />
<br />
<br />
