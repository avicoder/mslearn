---
    layout: post
    title: Access Metrics from your Azure Blob Storage Containers Programmatically - Access Azure Storage Metrics in Code
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/access-blob-storage-metrics-from-code/4-access-azure-storage-metrics/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/access-blob-storage-metrics-from-code.svg">
####  1. You have created a service principal in Azure Active Directory, and you have successfully authenticated the service principal using the LoginSilentAsync method. When you call MetricDefinitions.ListAsync, you receive an access denied message. How should you resolve this problem?


<i class='far fa-square'></i> &nbsp;&nbsp;Call the Metrics.ListAsync method instead of the MetricDefinitions.ListAsync method.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Assign the service principal to an appropriate role in Azure.

<i class='far fa-square'></i> &nbsp;&nbsp;Create an access key for the service principal in Azure.
<br />
<br />
<br />

####  2. You have written code that successfully retrieves metric definitions for an Azure Storage account from Azure Monitor. Now you want to retrieve values of the UsedCapacity metric. Which method should you call?


<i class='far fa-square'></i> &nbsp;&nbsp;MetricDefinitions.ListAsync

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Metrics.ListAsync

<i class='far fa-square'></i> &nbsp;&nbsp;The monitor client constructor
<br />
<br />
<br />
