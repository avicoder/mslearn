---
    layout: post
    title: Explore non-relational data offerings in Azure 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/explore-non-relational-data-offerings-azure/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/explore-non-relational-data-offerings-azure.svg">
####  1. What are the elements of an Azure Table storage key?


<i class='far fa-square'></i> &nbsp;&nbsp;Table name and column name

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Partition key and row key

<i class='far fa-square'></i> &nbsp;&nbsp;Row number
<br />
<br />
<br />

####  2. When should you use a block blob, and when should you use a page blob?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a block blob for unstructured data that requires random access to perform reads and writes. Use a page blob for discrete objects that rarely change.

<i class='far fa-square'></i> &nbsp;&nbsp;Use a block blob for active data stored using the Hot data access tier, and a page blob for data stored using the Cool or Archive data access tiers.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use a page block for blobs that require random read and write access. Use a block blob for discrete objects that change infrequently.
<br />
<br />
<br />

####  3. Why might you use Azure File storage?


<i class='far fa-square'></i> &nbsp;&nbsp;To share files that are stored on-premises with users located at other sites.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To enable users at different sites to share files.

<i class='far fa-square'></i> &nbsp;&nbsp;To store large binary data files containing images or other unstructured data.
<br />
<br />
<br />

####  4. You are building a system that monitors the temperature throughout a set of office blocks, and sets the air conditioning in each room in each block to maintain a pleasant ambient temperature. Your system has to manage the air conditioning in several thousand buildings spread across the country/region, and each building typically contains at least 100 air-conditioned rooms. What type of NoSQL data store is most appropriate for capturing the temperature data to enable it to be processed quickly?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Send the data to an Azure Cosmos DB database and use Azure Functions to process the data.

<i class='far fa-square'></i> &nbsp;&nbsp;Store the data in a file stored in a share created using Azure File Storage.

<i class='far fa-square'></i> &nbsp;&nbsp;Write the temperatures to a blob in Azure Blob storage.
<br />
<br />
<br />
