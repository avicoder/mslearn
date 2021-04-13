---
    layout: post
    title: Message queues and stream processing - Message queues- Case study
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-message-queues-streams/2-message-queues-case-study/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/message-queues-stream-processing.svg">
####  1. How would you organize messages in a Kafka cluster, if you needed them to be processed in order by consumers?


<i class='far fa-square'></i> &nbsp;&nbsp;Messages can be published in round-robin order over multiple Kafka topics. Kafka guarantees the order of messages across topics using a sequence number.

<i class='far fa-square'></i> &nbsp;&nbsp;Messages must be published within a Kafka topic, as all messages within a Kafka topic are guaranteed to be in order.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Messages must be published within a partition in a Kafka topic, as all messages within a partition are guaranteed to be ordered.
<br />
<br />
<br />
