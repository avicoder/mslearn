---
    layout: post
    title: Tune hyperparameters with Azure Machine Learning 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/tune-hyperparameters-with-azure-machine-learning/6a-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/tune-hyperparameters-with-azure-machine-learning.svg">
####  1. You plan to use hyperparameter tuning to find optimal discrete values for a set of hyperparameters. You want to try every possible combination of a set of specified discrete values. Which kind of sampling should you use?


<i class='far fa-square'></i> &nbsp;&nbsp;Random Sampling

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Grid Sampling

<i class='far fa-square'></i> &nbsp;&nbsp;Bayesian Sampling
<br />
<br />
<br />

####  2. You are using hyper parameter tuning to train an optimal model based on a target metric named "AUC". What should you do in your training script?


<i class='far fa-square'></i> &nbsp;&nbsp;Import the logging package and use a logging.info() statement to log the AUC

<i class='far fa-square'></i> &nbsp;&nbsp;Include a print() statement to write the AUC value to the standard output stream

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Get a reference to the Azure ML run context and use a run.log() statement to write the AUC value to the run log
<br />
<br />
<br />
