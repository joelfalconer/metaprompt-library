# Full-Text Prompt Restoration

The foundation repository published useful compact execution cards, but many were not faithful full-text restorations of their source programmes. This branch preserves the compact files and adds full restored candidates with explicit lineage.

Restoration states:

- `exact_full_prompt`: recovered verbatim from the supplied full-chat export;
- `package_recovered`: recovered from a source package;
- `expanded_reconstruction`: rebuilt from compact prompt, transcript evidence, related outputs and gate behaviour;
- `referenced_missing`: known artifact still requiring Library/Git/package recovery.

No restored prompt becomes stable merely because it is longer. `MPL-FULLTEXT-EVAL-001` must compare full and compact variants across unrelated domains, partial-source cases, private domains, owner-review tasks and implementation work.

The complete source concordance, 130 exact user prompt blocks, 151 Work Item prompts and successor release remain in the persistent Constellation handoff package. This repository receives the public context-agnostic candidates only.