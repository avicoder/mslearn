---
    layout: post
    title: Learn how concurrency works in Go 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/go-concurrency/6-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/go/go-concurrency.svg">
####  1. What's the correct syntax to create a goroutine?


<i class='far fa-square'></i> &nbsp;&nbsp;func (){}()

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;go launch()

<i class='far fa-square'></i> &nbsp;&nbsp;goroutine launch()`

<i class='far fa-square'></i> &nbsp;&nbsp;thread launch()
<br />
<br />
<br />

####  2. What's the purpose of using channels in Go?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To communicate properly within goroutines and avoid sharing memory for communication purposes.

<i class='far fa-square'></i> &nbsp;&nbsp;It's just another way of creating goroutines.

<i class='far fa-square'></i> &nbsp;&nbsp;To send data when doing HTTP calls to another API.

<i class='far fa-square'></i> &nbsp;&nbsp;To communicate between classes.
<br />
<br />
<br />

####  3. What's a particular feature of unbuffered channels?


<i class='far fa-square'></i> &nbsp;&nbsp;Channels that are dynamic. They can grow as you need automatically.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Sending data and receiving data in channels are blocking operations.

<i class='far fa-square'></i> &nbsp;&nbsp;Channels that you can pass by reference only.
<br />
<br />
<br />

####  4. How do you send data to a channel?


<i class='far fa-square'></i> &nbsp;&nbsp;ch = "Hi"

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;ch <- "Hi"

<i class='far fa-square'></i> &nbsp;&nbsp;send(ch, "Hi")
<br />
<br />
<br />

####  5. How do you receive data from a channel?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;res := <- ch

<i class='far fa-square'></i> &nbsp;&nbsp;res := get(ch)

<i class='far fa-square'></i> &nbsp;&nbsp;res := ch<-
<br />
<br />
<br />
