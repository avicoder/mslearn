---
    layout: post
    title: Detect and mitigate unfairness in models with Azure Machine Learning 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/detect-mitigate-unfairness-models-with-azure-machine-learning/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/detect-and-mitigate-unfairness-in-models-with-azure-machine-learning.svg">
####  1. You are training a binary classification model to support admission approval decisions for a college degree program. How can you evaluate if the model is fair, and doesn't discriminate based on ethnicity?


<i class='far fa-square'></i> &nbsp;&nbsp;Evaluate each trained model with a validation dataset, and use the model with the highest accuracy score. An accurate model is inherently fair.

<i class='far fa-square'></i> &nbsp;&nbsp;Remove the ethnicity feature from the training dataset.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Compare disparity between selection rates and performance metrics across ethnicities.
<br />
<br />
<br />

####  2. You have used Fairlearn to evaluate a model in a notebook. You register the model in your Azure Machine Learning workspace. You want to be able to select the model in Azure Machine Learning studio and from there view its fairness dashboard to compare disparity for performance metrics. What should you do?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Run an experiment in which you upload the dashboard metrics for the model.

<i class='far fa-square'></i> &nbsp;&nbsp;Save the notebook in your Azure Machine Learning workspace.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the selection_rate_group_summary function to get the fairness data, and save it as a file dataset in your Azure Machine Learning workspace.
<br />
<br />
<br />

####  3. You plan to use the Grid Search mitigation technique to find an optimal model for a binary classifier that predicts whether or not a candidate will be successful in an employment role. You want to ensure that the model selects an equal number of candidates from each category in the Gender feature. Which parity constraint should you use?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Demographic parity.

<i class='far fa-square'></i> &nbsp;&nbsp;Error rate parity.

<i class='far fa-square'></i> &nbsp;&nbsp;Bounded group loss.
<br />
<br />
<br />
