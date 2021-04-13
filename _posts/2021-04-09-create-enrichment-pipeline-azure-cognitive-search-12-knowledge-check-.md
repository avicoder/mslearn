---
    layout: post
    title: Create a custom skill for Azure Cognitive Search 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/create-enrichment-pipeline-azure-cognitive-search/12-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/create-an-enrichment-pipeline.svg">
####  1. You want to include a sentiment score for each document in an index. What should you do?


<i class='far fa-square'></i> &nbsp;&nbsp;Create a custom skill that uses an Azure Machine Learning model to predict the sentiment for a document

<i class='far fa-square'></i> &nbsp;&nbsp;Create a custom skill that calls the Text Analytics cognitive service to predict the sentiment of each document.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add the built-in Sentiment skill to the skillset used by the indexer.
<br />
<br />
<br />

####  2. You have implemented a custom skill as an Azure function. You want to include the custom skill in your Azure Cognitive Search indexing process. What should you do?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add a WebApiSkill to a skillset, referencing the Azure function's URI

<i class='far fa-square'></i> &nbsp;&nbsp;Create a JSON document with the input schema for your function, and save it in the folder where the documents to be indexed are stored.

<i class='far fa-square'></i> &nbsp;&nbsp;Submit each document to the function, and store the output in a separate data source. Then use the Merge skill to add the results to the index.
<br />
<br />
<br />
