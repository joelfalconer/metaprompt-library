---
id: mp.source.occurrence-fabric
title: Source and Occurrence Fabric
domain: source_knowledge
type: compiler
status: candidate
version: 0.1.0
summary: Creates stable evidence addresses for extracted occurrences across source snapshots and representations.
tags: [occurrence-uid, source-addressing, coverage, database]
source_lineage: [Gate R1 source and occurrence fabric]
canonical_effect: none_until_adopted
---

# Source and Occurrence Fabric

Build a source namespace, representation registry, turn concordance, chunk namespace and global occurrence index.

Every occurrence receives a stable UID resolving to one known source representation and source range. Aligned snapshots remain distinct representations. Scope anomalies are preserved for review rather than called missing data. Coverage identifies every turn and chunk with or without occurrences. No semantic merging occurs in this gate. Produce a queryable database or equivalent index and an integrity report.

Stop if source identities or ranges cannot be verified. Do not mutate previously issued occurrence UIDs in later gates.
