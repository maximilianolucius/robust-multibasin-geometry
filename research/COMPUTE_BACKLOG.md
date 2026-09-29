# Compute Backlog

## P0 — infrastructure

### C-B001 — solver cross-validation
Build two independent history-retaining Caputo solvers and validate on known solutions.

### C-B002 — nominal multibasin reproduction
Reproduce a published strong/Double-Allee multistable regime with extinction and survival/coexistence outcomes.

## P1 — uncertainty decomposition

### C-B010 — theta-only atlas
Sweep a declared ecological parameter box with fixed alpha. Track equilibria, local stability, and conservative basin classifications.

### C-B011 — alpha-only atlas
With fixed RHS parameters, vary alpha/order vectors. Remember equilibrium roots do not move from alpha alone.

### C-B012 — joint alpha-theta atlas
Map joint uncertainty only after separate effects are understood.

### C-B013 — kernel uncertainty
Attempt only if the Chief defines a mathematically coherent kernel class and common state space.

## P1 — robust basin objects

### C-B020 — common survival/extinction approximations
Approximate
\[
S_{\rm rob}=\bigcap_{u\in\mathcal U}S(u),
\qquad
E_{\rm rob}=\bigcap_{u\in\mathcal U}E(u)
\]
on the exact state slice defined by the Chief.

Do not infer universal validity from a finite grid.

### C-B021 — separator tracking
Track physical-slice separator/basin changes over uncertainty. Use adaptive refinement near classification boundaries.

### C-B022 — bistability-preservation map
Identify parameter/order regions where both target outcomes persist and where one disappears.

## P2 — validation/certification

### C-B030 — interval equilibrium/local stability boxes
Use interval arithmetic/branch-and-bound for equilibrium existence and fractional local stability over uncertainty boxes.

### C-B031 — robust invariant-set certification
If the Chief supplies a candidate common invariant/survival set, seek rigorous all-realizations certification.

### C-B032 — conservatism audit
Compare any analytic sufficient robust set with high-resolution set-oriented approximations to estimate how conservative it is.

## P3 — theorem discovery
Search numerical atlases for:
- monotonic separator motion;
- nested basin families;
- order monotonicity;
- topology-preserving regions;
- simple parameter invariants controlling loss of bistability.

These are conjecture generators, not theorems.

## P4 — figures
After theorem structure is fixed:
- nominal basin geometry;
- robust common-set atlas;
- separator envelope;
- alpha-vs-parameter theorem region;
- exact/certified box panel;
- conservatism comparison;
- convergence/horizon sensitivity.

Every figure must answer a theorem-level question.
