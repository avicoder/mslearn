---
    layout: post
    title: Train a machine learning model with Azure Machine Learning 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/train-local-model-with-azure-mls/5a-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/train-local-model-with-azure-mls-badge.svg">
####  1. You want to use a script-based experiment to train a PyTorch model, setting the batch size and learning rate hyperparameters to specified values each time the experiment runs. What should you do?


<i class='far fa-square'></i> &nbsp;&nbsp;Create multiple script files – one for each batch size and learning rate combination you want to use.

<i class='far fa-square'></i> &nbsp;&nbsp;Set the batch_size and learning_rate properties of the ScriptRunConfig before running the experiment.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add arguments for batch size and learning rate to the script, and set them in the arguments property of the ScriptRunConfig.
<br />
<br />
<br />

####  2. You have run an experiment to train a model. You want the model to be stored in the workspace, and available to other experiments and published services. What should you do?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Register the model in the workspace.

<i class='far fa-square'></i> &nbsp;&nbsp;Save the model as a file in a Compute Instance.

<i class='far fa-square'></i> &nbsp;&nbsp;Save the experiment script as a notebook.
<br />
<br />
<br />
