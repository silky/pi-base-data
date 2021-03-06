---
uid: I000217
if:
  and:
  - sigma-compact: true
  - t_2: true
then:
  metacompact: true
---
Let $X=\bigcup_{n<\omega}K_n$ for $K_n$ compact where $K_{n+1}\supseteq K_n$, and let $\mathcal U$ be an open cover of $X$. Then choose finite subcovers $\mathcal F_n$ of $\mathcal U$ for each $K_n$, and let $\mathcal F_0'=\mathcal F_0$. Since compact subsets of Hausdorff spaces are closed, $U\setminus K_n$ is open for any open set. So $\mathcal F_{n+1}' = \{U \setminus K_n:U\in \mathcal F_n\}$ is a finite open refinement covering $K_{n+1}\setminus K_n$.

Thus $\bigcup_{n<\omega}\mathcal F_n'$ covers $X$, and we claim it is a point-finite open refinement of $\mathcal U$. Let $x\in K_n$. It follows that $x$ does not belong in any member of $\mathcal F_{N}'$ for $N>n$. Thus $x$ is contained in finitely many members of $\bigcup_{n<\omega}\mathcal F_n'$.

