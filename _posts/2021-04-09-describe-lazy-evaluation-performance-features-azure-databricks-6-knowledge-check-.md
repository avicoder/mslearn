---
    layout: post
    title: Describe lazy evaluation and other performance features in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/describe-lazy-evaluation-performance-features-azure-databricks/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/describe-lazy-evaluation-other-performance-features-azure-databricks.svg">
####  1. Which of the following statements describes a wide transformations?


<i class='far fa-square'></i> &nbsp;&nbsp;A wide transformation can be applied per partition/worker with no need to share or shuffle data to other workers

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A wide transformation requires sharing data across workers. It does so by shuffling data.

<i class='far fa-square'></i> &nbsp;&nbsp;A wide transformation applies data transformation over a large number of columns
<br />
<br />
<br />

####  2. Which feature of Spark determines how your code is executed?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Catalyst Optimizer

<i class='far fa-square'></i> &nbsp;&nbsp;Tungsten Record Format

<i class='far fa-square'></i> &nbsp;&nbsp;Java Garbage Collection
<br />
<br />
<br />

####  3. If you create a DataFrame that will read some data from Azure Blob Storage, and then you create another DataFrame by filtering the initial DataFrame. What feature of Spark causes these transformation to be analyzed?


<i class='far fa-square'></i> &nbsp;&nbsp;Tungsten Record Format

<i class='far fa-square'></i> &nbsp;&nbsp;Java Garbage Collection

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Lazy Execution
<br />
<br />
<br />
