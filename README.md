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


Bijectivity means that each unique node in graph $A$ can be mapped to a corresponding unique node in graph $B$. This means that there must be the same number of nodes in both graphs. <br><br>
A graph is completely connected when every pair of distinct vertices is connected by a unique edge. <br><br>
Consider the edge between distinct nodes $u$ and $v$ in graph $A$. Because A is completely connected, there must be an edge between them. And since both graphs are bijective, $(f(u), f(v))$ must exist in graph $B$. This goes for every vertex in both graphs.<br><br>
$\therefore$ If $A$ and $B$ are bijective $(f: V_1 \rightarrow V_2)$  and there exists a unique edge between each pair of distinct vertices in each graph $((u,v) \in E_1$ iff $(f(u),f(v)) \in E_2)$, then they must be isomorphic.



