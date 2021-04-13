---
    layout: post
    title: Solve graph coloring problems by using Grover's search 
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/solve-graph-coloring-problems-grovers-search/8-knowledge-check/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/quantum/solve-graph-coloring-problems-grovers-search.svg">
####  1. You apply a marking oracle that implements the check "Are two bits of the input different?" to a state $\frac12 (|00\rangle + |01\rangle + |10\rangle + |11\rangle) \otimes |1\rangle$, where the first two qubits are the input register and the last qubit is the output qubit. What will the state be after the oracle application?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;$\frac12 (|00\rangle \otimes |1\rangle + |01\rangle \otimes |0\rangle + |10\rangle \otimes |0\rangle + |11\rangle \otimes |1\rangle)$

<i class='far fa-square'></i> &nbsp;&nbsp;$\frac12 (|00\rangle - |01\rangle - |10\rangle + |11\rangle) \otimes |1\rangle$

<i class='far fa-square'></i> &nbsp;&nbsp;$\frac12 (|00\rangle \otimes |0\rangle + |01\rangle \otimes |1\rangle + |10\rangle \otimes |1\rangle + |11\rangle \otimes |0\rangle)$
<br />
<br />
<br />

####  2. You're trying to solve a problem, and it turns out that exactly half of the possible inputs are solutions to the problem. How will the number of iterations affect the success probability of Grover's algorithm?


<i class='far fa-square'></i> &nbsp;&nbsp;The success probability first increases to nearly 100\%, then decreases to nearly 0\%, then increases again, and so on.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The success probability remains the same regardless of the number of iterations.

<i class='far fa-square'></i> &nbsp;&nbsp;The success probability first decreases to nearly 0\%, then increases to nearly 100\%, then decreases again, and so on.
<br />
<br />
<br />

####  3. Which of these problems would benefit the most from a quantum speedup offered by Grover's search algorithm?


<i class='far fa-square'></i> &nbsp;&nbsp;A database search, such as checking whether a table contains the given element

<i class='far fa-square'></i> &nbsp;&nbsp;A 2-SAT problem: Boolean satisfiability problem with at most two literals per clause

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A cryptographic problem, such as decrypting symmetric cryptography keys
<br />
<br />
<br />
