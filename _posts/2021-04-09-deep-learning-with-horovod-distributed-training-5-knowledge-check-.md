---
    layout: post
    title: Deep learning with Horovod for distributed training 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/deep-learning-with-horovod-distributed-training/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/deep-learning-with-horovod-distributed-training.svg">
####  1. Which of the following are utilized in the construction of a neural network?


<i class='far fa-square'></i> &nbsp;&nbsp;Learning rate.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Activation function.

<i class='far fa-square'></i> &nbsp;&nbsp;Loss function.
<br />
<br />
<br />

####  2. What is the size, rank, and local rank when using Horovod to train a deep learning model on two servers, each with two GPUs?


<i class='far fa-square'></i> &nbsp;&nbsp;Size = 2, Rank: [0, 1, 2, 3], and Local Rank: [0, 1]

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Size = 4, Rank: [0, 1, 2, 3], and Local Rank: [0, 1]

<i class='far fa-square'></i> &nbsp;&nbsp;Size = 2, Rank: [1, 2, 3, 4], and Local Rank: [1, 2]
<br />
<br />
<br />

####  3. In the Horovod training script, what is the primary purpose of hvd.callbacks.BroadcastGlobalVariablesCallback(0) callback?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To ensure consistent initialization of all workers when training is started with random weights or restored from a checkpoint.

<i class='far fa-square'></i> &nbsp;&nbsp;To average metrics among workers at the end of every epoch.

<i class='far fa-square'></i> &nbsp;&nbsp;Reduce the learning rate if training plateaus.
<br />
<br />
<br />
