---
uid: I000229
if:
  and:
  - first-countable: true
  - us: true
then:
  t_2: true
---
Assume $X$ is not Hausdorff. Then there are two points $x, y \in X$, $x \neq y$ such that $U \cap V \neq \emptyset$ for every pair of neighborhoods $U$ of $x$ and $V$ of $y$. Since $X$ is first-countable there is a countable neighborhood basis $U_n$ of $x$ and $V_n$ of $y$. Since $U_n \cap V_n \neq \emptyset$ for all $n$ choose any $x_n \in U_n \cap V_n$. It follows that $x_n \to x$ and $x_n \to y$ but this contradicts the US property.

