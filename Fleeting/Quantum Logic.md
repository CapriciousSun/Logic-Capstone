20260225145123

Tags: 

## + Formalism +
Quantum logic is not based upon the Hilbert space $\mathcal{H}$. Rather, it is an attempt to represent the Hilbert space in terms of some non-distributive orthocomplemented lattice. 
### ++ States ++
The states of some particle in a Hilbert space is represented as *propositions* in quantum logic. Manipulation of these propositions is the central dogma of quantum logic. 

### ++ Non-Distributivity ++
Classically, logic is distributive, where for some $p$, $q$, and $r$, that are propositions, $p \land (q \lor r) \Vdash (p \land q) \lor (p \land r)$. Quantum mechanically, this would not be valid. Given that the following states for some [[Particles|particle]]
- $p = \text{the particle has momentum in the interval } [0, \frac{1}{6}]$
- $q = \text{the particle is in the interval } [-1, 1]$
- $r = \text{the particle is in the interval } [1, 3]$
it is true that $p \land (q \lor r)$, since a particle having positions from $-1$ and $-3$ and momentum from $0$ to $\frac{1}{6}$ is valid. However, $(p \land q) \lor (p \land r)$ would not be valid, since the constraints on the positions and momentum are simultaneous. The resulting relations would be $\left( \left[ 0, \frac{1}{6} \right] \land [-1, 1] \right) \lor \left( \left[ 0, \frac{1}{6} \right] \land [1, 3] \right)$, which would not be valid under the Heisenberg Uncertainty Principle. To represent this as a [[Lattices|lattice]], the first theorem would be that a lattice $(L, \unlhd)$ is not distributive as well. From this, it could be said that a power set $\wp(X)$ could not include elements from lattice $(L, \unlhd)$. 

## + Motivation +
The motivation for having a logic distinct from classical (physical) logic is due to classical logic not fulfilling the physical requirements that quantum mechanics has. 
___
# References
[Quantum Logic and Probability Theory](https://plato.stanford.edu/entries/qt-quantlog/)
