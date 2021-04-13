---
    layout: post
    title: Store application data with Azure Blob storage - Clean up and knowledge check
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/store-app-data-with-azure-blob-storage/8-cleanup-next-steps-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/store-app-data-with-azure-blob-storage.svg">
####  1. Which of the following describes a good strategy for creating storage accounts and blob containers for your application?


<i class='far fa-square'></i> &nbsp;&nbsp;Create both your Azure Storage accounts and containers before deploying your application.

<i class='far fa-square'></i> &nbsp;&nbsp;Create Azure Storage accounts in your application as needed. Create the containers before deploying the application.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Create Azure Storage accounts before deploying your app. Create containers in your application as needed.
<br />
<br />
<br />

####  2. Which of the following can be used to initialize the Blob Storage client library within an application?


<i class='far fa-square'></i> &nbsp;&nbsp;An Azure username and password.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The Azure Storage account connection string.

<i class='far fa-square'></i> &nbsp;&nbsp;A globally-unique identifier (GUID) that represents the application.

<i class='far fa-square'></i> &nbsp;&nbsp;The Azure Storage account datacenter and location identifiers.
<br />
<br />
<br />

####  3. What happens when you call GetBlockBlobReference with the name of a blob?


<i class='far fa-square'></i> &nbsp;&nbsp;A new block blob is created in storage.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A CloudBlockBlob object is created locally. No network calls are made.

<i class='far fa-square'></i> &nbsp;&nbsp;An exception is thrown if the blob does not exist in storage.

<i class='far fa-square'></i> &nbsp;&nbsp;The contents of the named blob are downloaded.
<br />
<br />
<br />
