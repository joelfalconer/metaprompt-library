---
id: mp.source.sandbox-estate
title: Sandbox and Working-Directory Source Estate Inventory
domain: source_knowledge
type: audit
status: candidate
version: 0.1.0
summary: Inventories a temporary filesystem without destructive reorganization and builds a source/representation graph.
tags: [sandbox, inventory, custody, deduplication]
source_lineage: [sandbox reconsolidation practice]
canonical_effect: none_until_adopted
---

# Sandbox and Working-Directory Source Estate Inventory

Inspect the accessible sandbox or working directory before moving or consolidating anything. For each file, archive member and extracted tree, record byte identity, representation type, likely logical identity, provenance, custody, related sources, canonical status and proposed destination.

Required distinction: byte identity is not representation identity, semantic identity or canonical identity.

Hash before deduplication; index archives without assuming extracted trees are canonical; preserve raw and historical packages; treat transcript links as references rather than custody proof; track inaccessible artifacts as recovery objects; organize through generated indexes before physical moves; never invent a sandbox download path.

Return inventory, duplicate families, missing-source queue, representation graph, proposed non-destructive projection and preservation receipt.
