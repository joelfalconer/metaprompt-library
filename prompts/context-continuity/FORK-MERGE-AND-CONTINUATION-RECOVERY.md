---
id: mp.context.fork-recovery
title: Fork Merge and Continuation Recovery
domain: context_continuity
type: audit
status: candidate
version: 0.1.0
summary: Reconciles divergent chat or workflow forks after stale-state, timeout or
  accidental branching incidents.
tags:
- fork-recovery
- stale-state
- continuation
- merge
source_lineage:
- fork merge and continuation package
canonical_effect: none_until_adopted
---

# Fork Merge and Continuation Recovery

## Mission

Given a common base and two or more continuation forks, reconstruct what happened, preserve unique work, detect stale-state writes, and establish one safe continuation point.

## Procedure

1. Verify the exact common base and each fork's terminal turn or revision.
2. Build a turn and artifact concordance.
3. Classify each change as unique, duplicated, conflicting, stale, interrupted, superseded or externally advanced.
4. Distinguish conversational sequence from durable provider state.
5. Re-read current repositories or systems before selecting the live continuation.
6. Merge unique artifacts non-destructively; do not splice prose into fictional chronology.
7. Preserve both fork tails and record rejected state assumptions.
8. Produce a canonical current-state packet, missing-artifact queue, and exact next gate.

## Safety law

Stable provider identity and fresh state beat a fork's memory of what happened.
