20260225151655

Tags: 

## + Formalism +
A lattice is a [[Ordering Relations#Partial Order|partially ordered set]] where the pair $(L, \unlhd)$ has a meet and a join. 
### ++ Completeness ++
A lattice is complete if every subset $L$ has [[Ordering Relations#Meet and Join|a meet and join]]. $\wp(X)$ is a complete lattice for all subsets, including the set of all subspaces of a vector space. 

### ++ Distributivity ++

## + Orthocomplemented Lattices +
An ortholattice, or orthocomplemented lattice, is a lattice where it is possible to to pick out a complement $p'$ for every element $p$. The element and its complement must fulfill the conditions
- $p \unlhd q \to q' \unlhd p'$
- $p'' = p$
Formally, it is a structure such that $\mathcal{B} = (B, \sqsubseteq, ', 1, 0)$, where $\braket{\mathcal{B}, \sqsubseteq, 1, 0}$ is a bounded lattice and $\sqsubseteq$ is a [[Ordering Relations#Partial Order|partial ordering relation]] on $B$. Given this frame, any pair of elements $a$ and $b$ has an infimum $a \sqcap b$ and a supremum $a \sqcup b$ with the following conditions
- $a \sqcap b \sqsubseteq a, b$ and $\forall c: c \sqsubseteq a, b \curvearrowright c \sqsubseteq a \sqcap b$
- $a, b \sqsubseteq a \sqcup b$ and $\forall c: a, b \sqsubseteq c \curvearrowright a \sqcup b \sqsubseteq c$
- $\forall a: 0 \sqsubseteq a; a \sqsubseteq 1$
### ++ Orthocomplemented Operations ++
There are a few classical Boolean algebra operations that carry over
- Double negation $a'' = a$
- Contraposition $a \sqsubseteq b \curvearrowright b' \sqsubseteq a'$
- Non-contradiction $a \sqcap a' = 0$
Distributivity within an ortholattice is no obeyed, where
- $(a \sqcap b) \sqcup (a \sqcap c) \sqsubseteq a \sqcap (b \sqcup c)$
- $a \sqcup (b \sqcap c) \sqsubseteq (a \sqcup b) \sqcap (a \sqcup c)$

### ++ Value ++
For a pair $\mathcal{A} = \braket{ \mathcal{B}, v }$ or $\vDash_{\mathcal{A}} \alpha$ where $v$ is the valuation operator, where some formula is true if $v(\alpha) = 1$. Here, $\mathcal{A}$ is a model of $\alpha$. In fact, given some $T$ that $\vDash_{\mathcal{A}}T$, $\beta \in T$ where $\mathcal{A}$ is a model of it. 

## ++ Orthoframe ++
An orthoframe here is a structure $\mathcal{F} = \braket{ I, R }$, where $I$ is a non-empty set of worlds and $R$ is the accessibility relation that's reflexive and symmetric on I. This frame is based on a general Kripke frame, which would later be extended to a frame for [[Modal Logic B|modal logic B]]. A proposition within the orthoframe is a set of worlds $X$ that satisfies
$$\forall i [i \in X \iff \forall j (i \not\perp j \curvearrowright j \not\perp X )]$$
or that the proposition needs to contain only worlds that can access worlds that $X$ cannot access. 
___
# References
[The Basic Theory of Ordering Relations](https://plato.stanford.edu/entries/qt-quantlog/supplement.html)
