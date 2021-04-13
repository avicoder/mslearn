---
    layout: post
    title: Create customer Power BI reports in Dynamics 365 Customer Voice  
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-customer-power-bi-reports/7-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/create-customer-power-bi-reports.svg">
####  1. The Customer Service manager has heard that a Microsoft Power BI app is available that displays data from Dynamics 365 Customer Voice survey responses. The manager has access to Power BI but is not sure how to gain access to the app. What steps should the manager take to gain access?


<i class='far fa-square'></i> &nbsp;&nbsp;Open Power BI Desktop and then search for the Dynamics 365 Customer Voice Customer Satisfaction app in the visualizations section.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Sign in to Power BI, select Get data, search for the Dynamics 365 Customer Voice Customer Satisfaction app in AppSource, and then select Get it now to install the app.

<i class='far fa-square'></i> &nbsp;&nbsp;Sign in to Dynamics 365 Customer Voice, download the Dynamics 365 Customer Voice Customer Satisfaction app, and then import the app into Power BI Desktop.
<br />
<br />
<br />

####  2. A report writer has been asked to create a Power BI report by using records from an instance of Dynamics 365 Customer Voice. After downloading and installing Power BI Desktop, they need to get the correct data. Which data connection category should they start with?


<i class='far fa-square'></i> &nbsp;&nbsp;Database

<i class='far fa-square'></i> &nbsp;&nbsp;Online services

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Power Platform
<br />
<br />
<br />

####  3. A report writer is working on a custom report in Power BI Desktop. They want to know the number of survey invitations that have been sent and where the survey has been started but not yet submitted. Which method would provide the report writer with the accurate result?


<i class='far fa-square'></i> &nbsp;&nbsp;Add a chart visual to display all the survey invitations that were generated and sent by the actualstart date field from the msfp_surveyinvite entity.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add a card visual to display a Count (Distinct) of activityid from the msfp_surveyinvite entity, filtered by msfp_invitestatus to only show those with a status of Started.

<i class='far fa-square'></i> &nbsp;&nbsp;Add a table visual to list the details of all the survey invites from the msp_surveyinvite entity and list all the fields, including the msfp_invitestatus field.
<br />
<br />
<br />

####  4. The Customer Experience manager wants to analyze survey feedback and to review and filter data by using the Net Promoter Score feedback. The data on a Survey Response record in Dynamics 365 Customer Voice is stored as a number rather than showing the type of response given. What is the simplest way to display if a customer is considered Promoter, Passive, or Detractor based on the response that they gave?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create a new column on the msfp_surveyresponses entity called NPS Type by using a switch statement. This approach will show Promoters if 9 or above, Detractors if 6 or below, or Passive if a 7 or an 8. Add the column to the Power BI report.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a new measure on the msfp_surveyresponses entity called NPS Type to calculate the Net Promoter Score given, and then multiply by the average NPS from all responses.

<i class='far fa-square'></i> &nbsp;&nbsp;Create a new column on the contact entity called NPS Type by using a switch statement. This approach will show Promoters if 9 or above, Detractors if 6 or below, or Passive if a 7 or an 8. Add the column to the Power BI report.
<br />
<br />
<br />

####  5. The data for Dynamics 365 Customer Voice is made up of a series of entities that are stored in Dataverse. These entities can be linked together through specific fields, and report writers can then create reports in Power BI to share with their organization, providing a mechanism to analyze and filter the data as needed. Which of the following options are Dynamics 365 Customer Voice entities?


<i class='far fa-square'></i> &nbsp;&nbsp;msfp_question, msfp_surveyresponse, and msfp_surveyanswers

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;msfp_question, msfp_surveyresponse, and msfp_surveyinvite

<i class='far fa-square'></i> &nbsp;&nbsp;msfp_surveyinvite, msfp_surveydetails, and msfp_question
<br />
<br />
<br />
