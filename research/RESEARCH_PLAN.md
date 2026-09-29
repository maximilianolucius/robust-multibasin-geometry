# Research Plan

## Phase 0 — Define a common dynamical framework
1. Fix model class and uncertainty set \(\mathcal U\).
2. Separate uncertainty in ecological parameters, fractional orders, and memory kernel.
3. Define the correct physical and memory-state spaces.
4. Determine how systems with different alpha/kernel are compared on a common topology or common lift.
5. Define extinction/survival basins and robust/common versions with exact quantifiers.

Do not proceed with vague “uncertainty” language.

## Phase 1 — Subsumption audit
Re-check:
- robust persistence for semiflows;
- structured/delay robust persistence;
- viability and memo-viability;
- strong invariance/discriminating kernels;
- robust regions of attraction;
- attractor/separatrix continuation;
- structural stability.

Goal: identify the exact theorem that is not already routine.

## Phase 2 — Nominal multibasin structure
Choose a positive strong/Double-Allee class with analytically controlled:
- extinction state;
- survival/coexistence state;
- bistability;
- basin separator or at least a rigorously defined basin partition.

The nominal structure must be mathematically clean before uncertainty is added.

## Phase 3 — Perturbation theory for the basin decomposition
Seek structural results such as:
- persistence of attractors under parameter/order/kernel perturbation;
- continuation or controlled motion of a separator;
- upper/lower semicontinuity of basin sets;
- conditions preserving bistability;
- explicit mechanisms for topology loss.

## Phase 4 — Robust sets
Define and study objects such as:
\[
S_{\rm rob}=\bigcap_{u\in\mathcal U}S(u),
\qquad
E_{\rm rob}=\bigcap_{u\in\mathcal U}E(u),
\]
only after state-space meaning is rigorous.

Prefer maximal/sharp sets over arbitrary sufficient subsets.

Investigate inner/outer approximations with provable convergence or error if exact characterization is impossible.

## Phase 5 — Basin-relative persistence
On the survival side, connect robust basin geometry to persistence/permanence without pretending all positive states should persist.

## Phase 6 — Structured Double-Allee uncertainty
Use biologically meaningful correlated parameter/mechanism families. Distinguish parameter uncertainty that moves equilibria from alpha-only uncertainty that does not.

## Phase 7 — Certified computation
Use interval arithmetic, set-oriented methods, continuation, global optimization and validated numerics to support sharp statements.

## Phase 8 — Manuscript
Enter only after a principal theorem is proved/certified and clearly exceeds standard robust-persistence/viability machinery.

Follow agent_directives_publishable_first_submission.md and the <=25-page hard ceiling.
