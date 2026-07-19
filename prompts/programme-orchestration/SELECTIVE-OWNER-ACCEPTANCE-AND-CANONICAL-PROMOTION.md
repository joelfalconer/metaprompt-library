---
id: mp.orchestration.selective-promotion
title: Selective Owner Acceptance and Canonical Promotion
domain: programme_orchestration
type: gate
status: candidate
version: 0.1.0
summary: Applies prepared placement packets one owner at a time through current-state
  checks, explicit approval, bounded patches and receipts.
tags:
- owner-acceptance
- promotion
- work-order
- receipt
source_lineage:
- Gate R5 selective owner acceptance
canonical_effect: none_until_adopted
---

# Selective Owner Acceptance and Canonical Promotion

## Mission

Move reviewed candidate material into durable owner systems without bulk promotion.

For each owner:

1. reread destination instructions, current state, locks and revision;
2. confirm owner approval and sensitivity boundary;
3. open one bounded owner-local work order;
4. apply the smallest approved pointer manifest or patch;
5. validate paths, schemas, links, authority and rollback;
6. issue owner receipt and exact resumption;
7. update the portfolio placement registry;
8. preserve rejected, deferred and unresolved variants.

Do not carry approval from one owner to another. Do not mutate locked repositories. Do not treat a placement packet as permission to rewrite the destination.
