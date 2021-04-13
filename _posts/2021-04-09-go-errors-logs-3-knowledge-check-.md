---
    layout: post
    title: Implement error handling and logging in Go 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/go-errors-logs/3-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/go/go-errors-logs.svg">
####  1. What's the idiomatic way to handle errors in Go?


<i class='far fa-square'></i> &nbsp;&nbsp;Use a try/catch block.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use an if condition for a function that returns multiple values. The last value is the error.

<i class='far fa-square'></i> &nbsp;&nbsp;Use an if condition and check if the response is nil.

<i class='far fa-square'></i> &nbsp;&nbsp;Let the program terminate.
<br />
<br />
<br />

####  2. Which function can you use to create an error variable?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;errors.New('Employee not found!')

<i class='far fa-square'></i> &nbsp;&nbsp;fmt.Errorf('Employee not found!')

<i class='far fa-square'></i> &nbsp;&nbsp;error.New('Employee not found!')

<i class='far fa-square'></i> &nbsp;&nbsp;log.Error('Employee not found!')
<br />
<br />
<br />

####  3. Which of the following functions are in the log package?


<i class='far fa-square'></i> &nbsp;&nbsp;log.Print, log.Error, log.Info

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;log.Fatal, log.Print, log.Panic

<i class='far fa-square'></i> &nbsp;&nbsp;log.Info, log.Warn, log.Fatal

<i class='far fa-square'></i> &nbsp;&nbsp;log.Printf, log.Warning, log.Error
<br />
<br />
<br />

####  4. Which function can you use to configure logging to a file?


<i class='far fa-square'></i> &nbsp;&nbsp;log.SetOutputFile(file)

<i class='far fa-square'></i> &nbsp;&nbsp;log.SetFilePath(file)

<i class='far fa-square'></i> &nbsp;&nbsp;log.SetPath(file)

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;log.SetOutput(file)
<br />
<br />
<br />

####  5. Why would you want to use a logging framework?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;To configure logging levels, multiple outputs, and global contexts.

<i class='far fa-square'></i> &nbsp;&nbsp;To make your programs run slower.

<i class='far fa-square'></i> &nbsp;&nbsp;To simply configure structured logging.

<i class='far fa-square'></i> &nbsp;&nbsp;To write less code.
<br />
<br />
<br />
