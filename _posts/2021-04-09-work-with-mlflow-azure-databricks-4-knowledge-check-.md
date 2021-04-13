---
    layout: post
    title: Work with MLflow in Azure Databricks 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-with-mlflow-azure-databricks/4-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-with-mlflow-azure-databricks.svg">
####  1. What is the correct method to log model performance metrics, _rmse, in MLflow?


<i class='far fa-square'></i> &nbsp;&nbsp;mlflow.log("rmse", _rmse)

<i class='far fa-square'></i> &nbsp;&nbsp;mlflow.metric("rmse", _rmse)

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;mlflow.log_metric("rmse", _rmse)
<br />
<br />
<br />

####  2. What is the typical usage for mlflow.log_artifact method?


<i class='far fa-square'></i> &nbsp;&nbsp;Log model parameters.

<i class='far fa-square'></i> &nbsp;&nbsp;Log the pipeline model.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Log file or directory contents
<br />
<br />
<br />
