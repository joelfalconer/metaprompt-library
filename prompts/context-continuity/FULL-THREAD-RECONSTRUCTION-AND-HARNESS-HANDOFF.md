---
id: mp.context.full-thread-reconstruction
title: Full-Thread Reconstruction and Harness Handoff
domain: context_continuity
type: prompt_suite
status: candidate
version: 0.1.0
summary: Reconstructs a long conversation and its artifacts into a complete navigable
  package for continuation in another harness.
tags:
- reconstruction
- handoff
- source-custody
- long-context
source_lineage:
- full-thread ecosystem reconstruction prompt
canonical_effect: none_until_adopted
---

# Full-Thread Reconstruction and Harness Handoff

## Mission

Review the entire accessible thread, uploads, generated artifacts and relevant connected sources. Build a complete, durable and navigable package that preserves original sources, development history, current decisions, uncertainty and exact continuation state.

## Sequence

1. Build a source inventory before designing the final tree.
2. Preserve raw conversation and artifacts without rewriting them.
3. Create checksums and missing-source records.
4. Reconstruct system, project, concept and artifact relationships.
5. Separate source, working draft, candidate canon, accepted canon, superseded and unresolved material.
6. Produce topical dossiers without flattening substantial final artifacts.
7. Create local-harness orientation, read order, commands, active work, locks and next prompts.
8. Validate manifests, internal links, checksums and completeness claims.

## Minimum handoff

```yaml
handoff:
  mission:
  canonical_sources: []
  source_revisions: []
  accepted_decisions: []
  candidates: []
  active_work: []
  locks: []
  no_touch_paths: []
  artifacts_created: []
  missing_sources: []
  validation: []
  next_gate:
  exact_resume_point:
```

Never call a reconstruction a raw export. Never claim inaccessible files were reviewed.
