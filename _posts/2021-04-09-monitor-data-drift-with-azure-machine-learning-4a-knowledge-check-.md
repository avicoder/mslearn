---
    layout: post
    title: Monitor data drift with Azure Machine Learning 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/monitor-data-drift-with-azure-machine-learning/4a-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/monitor-data-drift-with-azure-machine-learning.svg">
####  1. You have trained a model using a dataset containing data that was collected last year. As this year progresses, you will collect new data. You want to track any changing data trends that might affect the performance of the model. What should you do?


<i class='far fa-square'></i> &nbsp;&nbsp;Collect the new data in a new version of the existing training dataset, and profile both datasets.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Collect the new data in a separate dataset and create a Data Drift Monitor with the training dataset as a baseline and the new dataset as a target.

<i class='far fa-square'></i> &nbsp;&nbsp;Replace the training dataset with a new dataset that contains both the original training data and the new data.
<br />
<br />
<br />

####  2. You are creating a data drift monitor. You want to automatically notify the data science team if a significant change in data distribution is detected. What must you do?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Define an AlertConfiguration and set a drift_threshold value.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the latency of the data drift monitor to allow time for data scientists to review the new data.

<i class='far fa-square'></i> &nbsp;&nbsp;Register the training dataset with the model, including the email address of the data science team as a tag.
<br />
<br />
<br />
