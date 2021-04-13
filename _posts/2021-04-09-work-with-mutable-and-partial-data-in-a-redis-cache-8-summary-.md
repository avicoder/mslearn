---
    layout: post
    title: Work with mutable and partial data in Azure Cache for Redis - Summary
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/work-with-mutable-and-partial-data-in-a-redis-cache/8-summary/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/work-with-mutable-and-partial-data-in-a-redis-cache.svg">
####  1. What happens if a command in a Redis transaction fails?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;If a command is queued with incorrect syntax, the transaction will be automatically discarded if you try to execute it. If a command fails during execution, the transaction will complete as normal.

<i class='far fa-square'></i> &nbsp;&nbsp;Commands prior to the failing command will still be executed, but those after the failing command will not be.

<i class='far fa-square'></i> &nbsp;&nbsp;The entire transaction will be rolled back.

<i class='far fa-square'></i> &nbsp;&nbsp;The connection will be aborted.
<br />
<br />
<br />

####  2. Which of the following is a Redis command for managing data expiration?


<i class='far fa-square'></i> &nbsp;&nbsp;DEL

<i class='far fa-square'></i> &nbsp;&nbsp;DISCARD

<i class='far fa-square'></i> &nbsp;&nbsp;TIMEOUT

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;EXPIRE
<br />
<br />
<br />

####  3. Your Redis cache is configured with the volatile-ttl eviction policy. If it runs out of memory and you try to insert a new key, which existing key is removed?


<i class='far fa-square'></i> &nbsp;&nbsp;The least recently used key.

<i class='far fa-square'></i> &nbsp;&nbsp;A random key.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The key that would next expire.

<i class='far fa-square'></i> &nbsp;&nbsp;A random key, selected from keys that have been configured to expire.
<br />
<br />
<br />
