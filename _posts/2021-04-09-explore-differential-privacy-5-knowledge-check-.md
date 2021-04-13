---
    layout: post
    title: Explore differential privacy 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/explore-differential-privacy/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/explore-differential-privacy.svg">
####  1. How does differential privacy work?


<i class='far fa-square'></i> &nbsp;&nbsp;All numeric values in the dataset are encrypted and cannot be used in analysis.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Noise is added to the data during analysis so that aggregations are statistically consistent with the data distribution but non-deterministic.

<i class='far fa-square'></i> &nbsp;&nbsp;All numeric column values in the dataset are converted to the mean value for the column. Analyses of the data use the mean values instead of the actual values.
<br />
<br />
<br />

####  2. In a differential privacy solution, what is the effect of setting an epsilon parameter?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A lower epsilon reduces the impact of an individual's data on aggregated results, increasing privacy and reducing accuracy

<i class='far fa-square'></i> &nbsp;&nbsp;A lower epsilon reduces the amount of noise added to the data, increasing accuracy and reducing privacy

<i class='far fa-square'></i> &nbsp;&nbsp;Setting epsilon to 1 enables differential privacy. Setting it to 0 disables differential privacy.
<br />
<br />
<br />
