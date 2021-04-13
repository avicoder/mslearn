---
    layout: post
    title: Virtualize computing power - Full virtualization vs. paravirtualization
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-virtualize-computing-power/2-full-virtualization/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/virtualize-computing-power.svg">
####  1. Critical instructions are problematic because they are:


<i class='far fa-square'></i> &nbsp;&nbsp;A subset of the set of privileged instructions; thus, they always trap if executed in user mode.

<i class='far fa-square'></i> &nbsp;&nbsp;A subset of the set of privileged instructions; thus, they do not trap if executed in user mode.

<i class='far fa-square'></i> &nbsp;&nbsp;A subset of the set of unprivileged instructions. They can modify the configuration of the system resources and trap if executed in user mode.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A subset of the set of unprivileged instructions. They can modify the configuration of the system resources and do not trap if executed in user mode.
<br />
<br />
<br />

####  2. Can an efficient hypervisor be constructed for an ISA with only one critical instruction?


<i class='far fa-square'></i> &nbsp;&nbsp;Yes

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;No
<br />
<br />
<br />

####  3. One way to deal with critical instructions is to scan the guest code before execution and replace the critical instructions with traps to the hypervisor. In what way is this approach efficient?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Allows most of the virtual environments to run in user space but without modifying the guest OS

<i class='far fa-square'></i> &nbsp;&nbsp;Is ideal for performance

<i class='far fa-square'></i> &nbsp;&nbsp;Allows most of the virtual environments to run in user space but would require a modification to the guest OS
<br />
<br />
<br />

####  4. The virtualization approach that executes a set of hypercalls that correspond to critical instructions is called:


<i class='far fa-square'></i> &nbsp;&nbsp;Code patching

<i class='far fa-square'></i> &nbsp;&nbsp;Emulation

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Paravirtualization

<i class='far fa-square'></i> &nbsp;&nbsp;Full virtualization
<br />
<br />
<br />

####  5. One of the most commonly used ISAs today is IA-32. IA-32 includes 17 critical instructions. Which of the following hypervisor types can be constructed for IA-32?


<i class='far fa-square'></i> &nbsp;&nbsp;A true or efficient hypervisor

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Hypervisor
<br />
<br />
<br />
