---
    layout: post
    title: Implement change tracking and file integrity monitoring for Windows IaaS VMs 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/implement-change-tracking-file-integrity-monitoring/08-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/implement-change-tracking-and-file-integrity-monitoring-for-windows-iaas-vms.svg">
####  1. Which of the following statements about enabling Change Tracking and Inventory is true?


<i class='far fa-square'></i> &nbsp;&nbsp;An administrator can use a Microsoft account as their Automation account providing it's in the same resource group as your Log Analytics workspace.

<i class='far fa-square'></i> &nbsp;&nbsp;A Log Analytics workspace must be in the same resource group as the Automation account.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Monitored Azure VMs can exist in any region, no matter the location of the Automation account.
<br />
<br />
<br />

####  2. Julia, an administrator at Contoso, wants to create an alert on registry changes to a VM named ContosoVM1. How should she configure the alert?


<i class='far fa-square'></i> &nbsp;&nbsp;From the home page of the Azure portal, select Virtual machines, and then select ContosoVM1. Under Settings, select Security, and then select New alert rule.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Select Security Center, then select File Integrity Monitoring. On the dashboard, select the appropriate workspace, and then select ContosoVM1. Then on the toolbar, select New alert rule.

<i class='far fa-square'></i> &nbsp;&nbsp;Select Security Center, then select File Integrity Monitoring. On the dashboard, select ContosoVM1. Then on the toolbar, select New alert rule.
<br />
<br />
<br />

####  3. An administrator at Contoso reviews the File Integrity Monitoring blade in Security Center, which has the following returned output. There are five workspaces. One is marked with UPGRADE PLAN, two are marked ENABLE, and two have both servers and changes listed.To enable File Integrity Monitoring on ContosoWorkspace, which currently displays the status of UPGRADE PLAN, what must the administrator do?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;They must upgrade the workspace to Security Center Standard tier.

<i class='far fa-square'></i> &nbsp;&nbsp;Nothing. They can use the workspace as is.

<i class='far fa-square'></i> &nbsp;&nbsp;It's not possible to use the specified workspace. They must choose one that's displaying the status ENABLE.
<br />
<br />
<br />
