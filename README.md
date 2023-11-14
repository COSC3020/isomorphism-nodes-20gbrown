[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12784439&assignment_repo_type=AssignmentRepo)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

## Proof

Considering two graphs A and B, with different numbers of nodes and not isomorphic: 

Graph A: $G_1 = (V_1, E_1)$

Graph B: $G_2 = (V_2, E_2)$

**Bijection function:**

$f: A ↔ B$

V<sub>A<sub>1</sub></sub> ↔ V<sub>B<sub>1</sub></sub>

V<sub>A<sub>2</sub></sub> ↔ V<sub>B<sub>2</sub></sub>

. . .

V<sub>A<sub>n</sub></sub> ↔ V<sub>B<sub>n</sub></sub>

Since $f$ is a bijection, it must map all nodes of graph $G_1$ to all nodes of graph $G_2$ in a one-to-one manner. 

However, it is impossible to find such a bijection in this case becase the graphs have a different number of nodes. In other words, if $G_1$ has $n$ nodes and $G_2$ has $m$ nodes, where $n /notequalto m$, then there is no way to map all the nodes of $G_1$ to all the nodes of $G_2$ in a one-to-one and onto manner. 

Therefore, it has been shown that if two graphs, $G_1$ and $G_2$, do not have the same number of nodes, they cannot be isomorphic.

