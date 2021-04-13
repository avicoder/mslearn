---
    layout: post
    title: Introduction to PowerShell 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/introduction-to-powershell/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/powershell/introduction-to-powershell.svg">
####  1. Using the help system, what command, or function, offers the best experience for finding out more about a command?


<i class='far fa-square'></i> &nbsp;&nbsp;{your command} --help

<i class='far fa-square'></i> &nbsp;&nbsp;Get-Help {your command}

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;help {your command}
<br />
<br />
<br />

####  2. Which statement is the best choice to filter left?


<i class='far fa-square'></i> &nbsp;&nbsp;Get-Process | Select-Object Name | Where-Object Name -eq name-of-process

<i class='far fa-square'></i> &nbsp;&nbsp;Get-Process | Where-Object Name -eq name-of-process | Select-Object name-of-process

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Get-Process -Name name-of-process | Select-Object Name
<br />
<br />
<br />

####  3. Which statement will most efficiently find the returned type from a command?


<i class='far fa-square'></i> &nbsp;&nbsp;{command} --type

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;{command} | Get-Member

<i class='far fa-square'></i> &nbsp;&nbsp;{command} | Get-Type

<i class='far fa-square'></i> &nbsp;&nbsp;{command} Get-Member
<br />
<br />
<br />
