# Chief ↔ Compute Coordination Protocol

## Ownership
Chief owns:
- scientific direction;
- literature/novelty judgments;
- CLAIMS, NOVELTY_MATRIX, SCOPE_MATRIX;
- theorem statements and proofs;
- definition of uncertainty and robust quantifiers;
- paper/.

Compute owns unless otherwise directed:
- computations/;
- tests/;
- generated data;
- generated figures;
- computational return reports.

## Paths
Chief request:
research/coordination/chief-to-compute/TASK-NNNN_<slug>_REQUEST.md

Compute return:
research/coordination/compute-to-chief/TASK-NNNN_<slug>_RETURN.md

Chief decision:
research/coordination/chief-decisions/TASK-NNNN_<slug>_DECISION.md

## Request requirements
Every request states:
- mathematical question;
- uncertainty set;
- quantifier: exists / for all / probability / numerical sample;
- required evidence class;
- inputs/ranges;
- allowed methods;
- tests;
- expected artifacts;
- stop conditions.

## Return requirements
Every return states:
- task ID;
- branch/final SHA;
- environment and dependency versions;
- exact commands;
- code/output paths;
- tests;
- result;
- evidence label: exact / certified / numerical;
- uncertainty coverage actually checked;
- caveats;
- suggested next question.

## Scientific discipline
A finite grid never proves a for-all uncertainty claim.

A weakly viable selection is not a robust invariant set.

A numerical separator envelope is not an exact basin theorem without certification.
