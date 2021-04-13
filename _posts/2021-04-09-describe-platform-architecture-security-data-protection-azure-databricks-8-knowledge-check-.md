---
    layout: post
    title: Describe platform architecture, security, and data protection in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/describe-platform-architecture-security-data-protection-azure-databricks/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/describe-platform-architecture-security-data-protection-azure-databricks.svg">
####  1. Which statement about the Azure Databricks Data Plane is true?


<i class='far fa-square'></i> &nbsp;&nbsp;The Data Plane contains the Cluster Manager and coordinates data processing jobs

<i class='far fa-square'></i> &nbsp;&nbsp;The Data Plane is hosted within a Microsoft-managed subscription

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The Data Plane is hosted within the client subscription and is where all data is processed and stored
<br />
<br />
<br />

####  2. In which modes does Azure Databricks provide data encryption?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;At-rest and in-transit

<i class='far fa-square'></i> &nbsp;&nbsp;At-rest only

<i class='far fa-square'></i> &nbsp;&nbsp;In-transit only
<br />
<br />
<br />

####  3. What does Azure Data Lake Storage (ADLS) Passthrough enable?


<i class='far fa-square'></i> &nbsp;&nbsp;Automatically mounting ADLS accounts to the workspace that are added to the managed resource group

<i class='far fa-square'></i> &nbsp;&nbsp;User security groups that are added to ADLS are automatically created in the workspace as Databricks groups

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Commands running on a configured cluster can read and write data in ADLS without configuring service principal credentials
<br />
<br />
<br />

####  4. What is an Azure Key Vault-backed secret scope?


<i class='far fa-square'></i> &nbsp;&nbsp;It is the Key Vault Access Key used to securely connect to the vault and retrieve secrets

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A Databricks secret scope that is backed by Azure Key Vault instead of Databricks

<i class='far fa-square'></i> &nbsp;&nbsp;It is a method by which you create a secure connection to Azure Key Vault from a notebook and directly access its secrets within the Spark session
<br />
<br />
<br />
