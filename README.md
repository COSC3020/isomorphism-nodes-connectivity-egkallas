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

Consider the graph $A$:
<br>
$V$  $E$<br>
$a | b$<br>
$b | c$<br>
$c | d$<br>
$d | a$<br>
<br>
Consider the graph $B$:<br>
$V$  $E$<br>
$w | x$<br>
$x | y$<br>
$y | z$<br>
$z | w$<br>
<br>
These graphs have the same number of nodes, which corresponds to bijectivity.<br>
Lemma: Bijectivity ($V_1 \rightarrow V_2$)<br>
$f(a) = w$<br>
$f(b) = x$<br>
$f(c) = y$<br>
$f(d) = z$<br>
This prooves every node in $A$ can be mapped to a unique node in $B$.<br><br>
A completely connected graph is defined as a graph where every pair of distinct vertices is connected by a pair of unique edges (one in each direction).
Examining the above graphs, this becomes apparent. <br><br>
Since both graph share the same completely connected structure, this indicates edge correspondence. <br>
Lemma: Edge correspondence ($(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$)<br>
$(a, b) \in E_1 \rightarrow (w, x) \in E_2$<br>
$(b, c) \in E_1 \rightarrow (x, y) \in E_2$<br>
$(c, d) \in E_1 \rightarrow (y, z) \in E_2$<br>
$(d, a) \in E_1 \rightarrow (z, w) \in E_2$<br><br>
This prooves that for every edge $(u,v)$ in $A$ there is a corresponding edge $(f(u),f(v))$ in $B$.<br><br>
The above graphs share the same number of nodes (which we can use to prove their bijectivity) and they are both completely connected (which we can use to prove their edge correspondence).<br>
$\therefore$ if $A$ and $B$ have these properties, they must be isomorphic. 



