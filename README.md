[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ppBU16qM)
# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Proof by contradiction:

Assume that two completely connected grpahs A and B, with the same number of nodes, 
are not isomorphic. This means that there exists an edge from some nodes n_0 to n_1
in A such that the same nodes n_0 and n_1 in B do not have an edge.

This means that the graph is not completely connected as it does not have edges between
all nodes in the graph.

A graph cannot be both completely connected and not completely connected at the same 
time, as this is a contradiction.

Therefore, if a graph is completely connected with the same number of nodes,
it has to be isomorphic by contradiction.
