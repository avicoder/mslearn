---
    layout: post
    title: Distributed computing on the cloud- GraphLab - Data structure and graph flow
    description: nil
    summary: nil
    tags: nil
---


 <a target="_blank" href="https://docs.microsoft.com/en-us/learn/modules/cmu-analytics-engines-graphlab/1-data-structure-graph-flow/"><i class="fas fa-external-link-alt"></i> </a>
 <img align="right" src="https://docs.microsoft.com/en-us/learn/achievements/cmu-cloud-developer/distributed-programming-graphlab.svg">
####  1. Complete the following sentences: 
Graph-parallel problems assume problems are modeled as ____________.
Computation in GraphLab is represented as ____________.
Data dependencies or communications are represented as ____________.


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;graphs, vertices, edges

<i class='far fa-square'></i> &nbsp;&nbsp;threads, edges, vertices

<i class='far fa-square'></i> &nbsp;&nbsp;tasks, vertices, edges

<i class='far fa-square'></i> &nbsp;&nbsp;threads, vertices, edges
<br />
<br />
<br />

####  2. What does atom generation entail?


<i class='far fa-square'></i> &nbsp;&nbsp;A graph is partitioned into individual atoms, which are encoded by using some form of binary representation.

<i class='far fa-square'></i> &nbsp;&nbsp;An atom consists of the actual vertices and edges that belong to a particular partition, which are stored as an adjacency matrix.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;A graph is partitioned into individual atoms and is self-contained with instructions on how to generate the vertices and edges that belong to that partition.

<i class='far fa-square'></i> &nbsp;&nbsp;A graph is stored in its entirety as an atom and stored on a distributed file system.
<br />
<br />
<br />

####  3. What does partition generation entail?


<i class='far fa-square'></i> &nbsp;&nbsp;A graph is partitioned based on the definitions in the atom index file.

<i class='far fa-square'></i> &nbsp;&nbsp;A graph adjacency matrix is equally partitioned among nodes in the cluster.

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;The commands in an atom's journal are played to generate the partition associated with an atom.
<br />
<br />
<br />

####  4. Assume the following graph: 
 
Assume that the scope of a vertex $v$ in this graph is defined as the immediate neighboring vertices of $v$. 
Which vertices have the largest scope?


<i class='far fa-square'></i> &nbsp;&nbsp;$V_{5}$

<i class='far fa-square'></i> &nbsp;&nbsp;$V_{2}$ and $V_{4}$

<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;$V_{1}$ and $V_{3}$

<i class='far fa-square'></i> &nbsp;&nbsp;$V_{6}$
<br />
<br />
<br />

####  5. Assume a graph partitioning strategy simply divided up a graph vertex-wise, and sends individual vertices (along with their neighboring edges and ghost vertices) to individual machines in a cluster. In which of the following cases will this strategy be suboptimal in terms of work distributed among the machines in a cluster?


<i class='fas fa-check-square' style='color: Dodgerblue;'></i> &nbsp;&nbsp;Graphs with a heavily skewed distribution of edges to vertices

<i class='far fa-square'></i> &nbsp;&nbsp;Graphs with directed edges

<i class='far fa-square'></i> &nbsp;&nbsp;Graphs with a very large number (> 1 million) of edges

<i class='far fa-square'></i> &nbsp;&nbsp;Graphs with a very large number (> 1 million) of vertices
<br />
<br />
<br />
