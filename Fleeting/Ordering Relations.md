20260225145809

Tags: 

## Formalism
An ordering, or a *partial ordering*, is some action on a set $P$ that's a reflexive, anti-symmetric, and transitive binary relation [[Subgroup|subgroup]] on $P$. Given propositions $p, q, r \in P$, the following rules can be obtained
1. $p \unlhd q$
2. $p \unlhd q \land q \unlhd p \leftrightarrow p = q$
3. $p \unlhd q \land q \unlhd r \to p \unlhd r$

## Partial Order
A partially ordered set, also called a *poset*, is a pair $(P, \unlhd)$ where $P$ is some set and $\unlhd$ is an ordering on $P$. 
#### Meet and Join
A meet, or the *greatest lower bound*, is given by the greatest element in $P$ that is below both $p$ and $q$, or $p \land q$ for $p, q \in P$. The join, or the *least upper bound*, $p$ and $q$ is the least element lying above $p$ and $q$, denoted as $p \lor q$. So, for any propositions $p, q, r \in P$, the following are true
1. $r \unlhd p \land q \to r \unlhd p \land r \unlhd q$
2. $p \lor q \unlhd r \to p \unlhd r \land q \unlhd r$
It should be said that $p \land p = p \lor p = p$ for all $p$ in $P$ and $p \unlhd q \leftrightarrow p\land q = p \leftrightarrow p \lor q = q$. 
___
# References
[SEP - The Basic Theory of Ordering Relations](https://plato.stanford.edu/entries/qt-quantlog/supplement.html)
