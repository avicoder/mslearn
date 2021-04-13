---
    layout: post
    title: Virtualize I/O - How Xen does I/O virtualization
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-virtualize-input-output/3-xen-virtualization/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/resource-virtualization-input-output.svg">
####  1. How does Xen Project avoid having device drivers for the hypervisor and the guest operating systems?


<i class='far fa-square'></i> &nbsp;&nbsp;By borrowing the device drivers provided in guest OSs

<i class='far fa-square'></i> &nbsp;&nbsp;By adopting a user-mode hosted virtualized system

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;By adopting a dual-mode hosted virtualized system and using only the device drivers defined at the host OS

<i class='far fa-square'></i> &nbsp;&nbsp;By collocating its hypervisor with a traditional OS and using only the device drivers defined at the hypervisor
<br />
<br />
<br />

####  2. In Xen, would every domain be vacant of virtual I/O devices and relevant drivers, including domain 0?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Yes

<i class='far fa-square'></i> &nbsp;&nbsp;No
<br />
<br />
<br />
