---
uid: I000120
if:
  and:
  - t_2: true
  - compact: true
then:
  t_4: true
---
First, note that if $X$ is compact and $T_2$, it is $T_3$. For given a closed set $B$ and a point $a \notin B$, for each $b \in B$, let $U_b$ and $V_b$ be disjoint open sets containing $a$ and $b$ respectively. Since $B$ is closed, it is compact and thus some finite subcollection $V_{b_i}$ covers $B$. Then $O_a = \cap_i U_{b_i}$ and $O_B = \cup V_{b_i}$ are disjoint open sets containing $a$ and $B$ respectively.

Similarly, if $A$ and $B$ are disjoint closed sets in $X$, then for each $b \in B$ there are open disjoint $U_b$ and $V_b$ containing $A$ and $b$ respectively. By compactness, some finite subcollection $V_{b_i}$ covers $B$. Then $O_A = \cap_i U_{b_i}$ and $O_B = \cup_i V_{b_i}$ are disjoint open sets continaing $A$ and $B$ respectively.

