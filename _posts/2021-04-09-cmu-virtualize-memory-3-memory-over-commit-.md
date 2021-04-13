---
    layout: post
    title: Virtualize memory - Memory overcommitment
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-virtualize-memory/3-memory-over-commit/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/virtualize-memory.svg">
####  1. Memory overcommitment implies that:


<i class='far fa-square'></i> &nbsp;&nbsp;The combined total size of the real memories equals the size of the physical memory.

<i class='far fa-square'></i> &nbsp;&nbsp;The combined total size of the real memories is less than the size of the physical memory.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The combined total size of the real memories is greater than the size of the physical memory.
<br />
<br />
<br />

####  2. Assume a hypervisor does not employ memory overcommitment. Assume also a physical memory of 9 GB. What is the maximum number of virtual machines that can be provisioned on such a hypervisor if the real memory of each VM should be at least 3 GB?


<i class='far fa-square'></i> &nbsp;&nbsp;1 VM

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;2 VMs

<i class='far fa-square'></i> &nbsp;&nbsp;3 VMs

<i class='far fa-square'></i> &nbsp;&nbsp;4 VMs

<i class='far fa-square'></i> &nbsp;&nbsp;As many VMs as we like
<br />
<br />
<br />

####  3. Assume a hypervisor employs memory overcommitment. To avoid information leaking among virtual machines during page reclamations, the hypervisor will:


<i class='far fa-square'></i> &nbsp;&nbsp;Reclaim pages that haven't been previously used by any VM.

<i class='far fa-square'></i> &nbsp;&nbsp;Avoid reclaiming pages.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Erase every reclaimed page irrespective of whether it's been used previously.
<br />
<br />
<br />
