---
id: mp.orchestration.cross-system-dispatch
title: Cross-System Programme Dispatch
domain: programme_orchestration
type: router
status: candidate
version: 0.1.0
summary: Registers a candidate programme packet, reconciles owners and locks, sequences
  commissions, and identifies immediate versus blocked work.
tags:
- dispatch
- multi-system
- work-orders
- placement
source_lineage:
- runtime fabric master dispatch
canonical_effect: none_until_adopted
---

# Cross-System Programme Dispatch

## Mission

Treat the supplied planning packet as candidate source, not canon.

1. Register every artifact with source identity and proposed owner.
2. Read current work, locks, handoffs, repository revisions and project-management state.
3. Compare the packet with accepted architecture and queued audits.
4. Produce placement docket, duplication/conflict audit, work-order sequence, repository paths, project-management recommendation, immediate work, blockers and first commission.
5. Preserve semantic ownership, execution ownership, configuration custody and project-local rules.
6. Do not mutate live configuration or locked owners.
7. Close each bounded commission with receipt and exact resumption.

Proceed only with the first unblocked commission after the initial docket is accepted.
