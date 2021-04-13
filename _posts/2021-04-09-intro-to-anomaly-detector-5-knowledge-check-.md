---
    layout: post
    title: Introduction to Anomaly Detector 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/intro-to-anomaly-detector/5-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/anomaly-detector.svg">
####  1. What is meant by seasonable data?


<i class='far fa-square'></i> &nbsp;&nbsp;Data based on the time or year it was recorded.

<i class='far fa-square'></i> &nbsp;&nbsp;How far apart the values are by default for each recorded period.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Data occurring at regular intervals.
<br />
<br />
<br />

####  2. What is the purpose of specifying granularity in your JSON data object?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It is used to indicate the recording pattern of the data.

<i class='far fa-square'></i> &nbsp;&nbsp;It tells the service how to chunk up the results that are returned for review, independent of the time series data pattern.

<i class='far fa-square'></i> &nbsp;&nbsp;It is used to indicate the range of acceptable values.
<br />
<br />
<br />

####  3. How does the Anomaly Detector API evaluate real-time data for anomalies?


<i class='far fa-square'></i> &nbsp;&nbsp;It collects all the values in a window of time and evaluates them all at once.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;It evaluates the current value against the previous value.

<i class='far fa-square'></i> &nbsp;&nbsp;It uses interpolation based on the current value and the previous value to predict what the expected value should be.
<br />
<br />
<br />
