---
    layout: post
    title: Protect your virtual machine settings with Azure Automation State Configuration - What is Azure Automation State Configuration?
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/protect-vm-settings-with-dsc/2-what-is-azure-automation-state-configuration/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/protect-vm-settings-with-dsc.svg">
####  1. What is Azure Automation State Configuration?


<i class='far fa-square'></i> &nbsp;&nbsp;A declarative management platform to configure, deploy, and control systems.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A service used to write, manage, and compile PowerShell Desired State Configuration (DSC) configurations, import DSC resources, and assign configurations to target nodes.

<i class='far fa-square'></i> &nbsp;&nbsp;A service that manages the state configuration on each destination, or node.
<br />
<br />
<br />

####  2. A PowerShell DSC script ______________.


<i class='far fa-square'></i> &nbsp;&nbsp;Contains the steps required to configure a virtual machine to get it into a specified state.

<i class='far fa-square'></i> &nbsp;&nbsp;Is idempotent.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Describes the desired state.
<br />
<br />
<br />

####  3. Why should you use pull mode instead of push mode for DSC?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Pull mode is best for complex environments that need redundancy and scale.

<i class='far fa-square'></i> &nbsp;&nbsp;Pull mode is easy to set up and doesn't need its own dedicated infrastructure.

<i class='far fa-square'></i> &nbsp;&nbsp;Pull mode uses the local configuration manager (LCM) to make sure that the state on each node matches the state specified by the configuration.
<br />
<br />
<br />
