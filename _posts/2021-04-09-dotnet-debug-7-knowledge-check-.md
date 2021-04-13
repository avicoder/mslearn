---
    layout: post
    title: Interactively debug .NET apps with the Visual Studio Code debugger 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/dotnet-debug/7-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/dotnet-debug.svg">
####  1. When you want to write a line to the debug console only when you're debugging, which API should you use?


<i class='far fa-square'></i> &nbsp;&nbsp;System.Console.WriteLine

<i class='far fa-square'></i> &nbsp;&nbsp;System.Diagnostics.Trace.WriteLine

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;System.Diagnostics.Debug.WriteLine

<i class='far fa-square'></i> &nbsp;&nbsp;System.WriteLine
<br />
<br />
<br />

####  2. If you want to write a debug message only when the count is 0, what code would you use?


<i class='far fa-square'></i> &nbsp;&nbsp;Debug.Assert(count != 0, "Count should not be 0.");

<i class='far fa-square'></i> &nbsp;&nbsp;Debug.Assert(count == 0, "Count should not be 0.");

<i class='far fa-square'></i> &nbsp;&nbsp;Debug.WriteIf(count != 0, "Count should not be 0.");

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Debug.WriteIf(count == 0, "Count should not be 0.");
<br />
<br />
<br />

####  3. What are the top two values a debugger provides?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Control of your program execution and observation of your program's state

<i class='far fa-square'></i> &nbsp;&nbsp;Modifying program values and changing your program output

<i class='far fa-square'></i> &nbsp;&nbsp;Observing your program's state and modifying your program values

<i class='far fa-square'></i> &nbsp;&nbsp;Editing your program while running and editing program values
<br />
<br />
<br />

####  4. Which Visual Studio Code debugger panel is most useful to observe the current value of a specific variable across different functions?


<i class='far fa-square'></i> &nbsp;&nbsp;Use the Variables panel because it shows all variables that are currently in scope.

<i class='far fa-square'></i> &nbsp;&nbsp;Hover over the variable in the code editor to display the value.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Use the Watch panel to select specific variables or expressions to watch throughout the program's execution.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the Call Stack panel.
<br />
<br />
<br />
