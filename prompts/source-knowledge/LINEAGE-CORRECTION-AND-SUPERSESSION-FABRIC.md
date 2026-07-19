---
id: mp.source.lineage-fabric
title: Lineage, Correction, and Supersession Fabric
domain: source_knowledge
type: compiler
status: candidate
version: 0.1.0
summary: Builds evidence-bearing aliases, corrections, contradictions, revisions,
  artifact ancestry and request-delivery relations above an immutable occurrence layer.
tags:
- lineage
- correction
- supersession
- artifact-ancestry
source_lineage:
- Gate R2 lineage fabric
canonical_effect: none_until_adopted
---

# Lineage, Correction, and Supersession Fabric

Given a verified occurrence fabric, build relation layers without changing occurrence UIDs.

Every edge must include source UIDs, evidence summary, confidence, competing hypotheses, review status and canonical effect.

Model separately:

- alias versus same identity;
- component, role, product, method and office relations;
- correction, contradiction, rename, revision and supersession;
- artifact family, representation, checksum and custody;
- request, attempt, mention, delivery, acceptance and rejection.

Preserve rejected and superseded variants. Detect cycles. Queue ambiguous identities and merges. Do not assign final canonical owners in this gate.
