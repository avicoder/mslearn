---
    layout: post
    title: Manage virtual machines with the Azure CLI - Summary and cleanup
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/manage-virtual-machines-with-azure-cli/9-cleanup/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/manage-virtual-machines-with-azure-cli.svg">
####  1. Suppose you're an administrator of several Azure virtual machines. You get a text message indicating some problems with your VMs. You are at a friend’s house and only have your tablet with you. True or false: you'll still be able to access the Azure CLI using the tablet, even though you can't install the CLI on it.


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;True

<i class='far fa-square'></i> &nbsp;&nbsp;False
<br />
<br />
<br />

####  2. Suppose you have a script that creates several VMs with different images. When the script issues the command to create the first VM you do not want to block the script while the VM is created, instead you want the script to immediately move on to the next command. What is the best way to do this?


<i class='far fa-square'></i> &nbsp;&nbsp;Add the '--async' argument to your create command.

<i class='far fa-square'></i> &nbsp;&nbsp;Use the ampersand (&) to run the process in the background.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Add the '--no-wait' argument to your create command.
<br />
<br />
<br />

####  3. Most Azure commands return JSON by default. Sometimes this data set can be very large which makes it difficult to read and tricky to use the result of one command as input to another command. What can you use with Azure CLI to filter the results to get only the data that you need?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;You can use the '--query' argument.

<i class='far fa-square'></i> &nbsp;&nbsp;You can use the '--filter' argument.

<i class='far fa-square'></i> &nbsp;&nbsp;You can pipe the results to a JSON parsing utility and use filtering capability there.
<br />
<br />
<br />
