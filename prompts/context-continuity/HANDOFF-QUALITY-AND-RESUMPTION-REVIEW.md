---
id: mp.context.handoff-review
title: Handoff Quality and Resumption Review
domain: context_continuity
type: evaluator
status: candidate
version: 0.1.0
summary: Adversarially tests whether a handoff can safely resume work without archaeology,
  drift or authority leakage.
tags:
- handoff
- quality-gate
- resumption
- continuity
source_lineage:
- handoff review doctrine
canonical_effect: none_until_adopted
---

# Handoff Quality and Resumption Review

Evaluate the handoff against:

1. **Source completeness:** are every named source and revision accessible?
2. **Temporal validity:** does it end at the actual latest source state?
3. **Authority validity:** who accepted each decision?
4. **State validity:** do provider reads match the packet?
5. **Lock validity:** are concurrent workers and no-touch paths current?
6. **Artifact validity:** do files, checksums and destinations exist?
7. **Contradiction handling:** are unresolved conflicts visible?
8. **Execution sufficiency:** can a fresh worker identify the exact next action, commands, done condition and rollback?
9. **Context economy:** does it load the minimum sufficient context rather than an archive avalanche?
10. **Canonical restraint:** is the handoff a projection from source state rather than a competing source of truth?

Return `ACCEPT`, `ACCEPT_WITH_CORRECTIONS`, or `REJECT_AND_RECONSTRUCT`, plus a corrected resumption packet.
