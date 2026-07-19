# Repository operating instructions

This repository is a context-agnostic public prompt library.

## Required workflow

1. Read `README.md`, `registry/taxonomy.yaml`, and `registry/prompts.yaml`.
2. Search the registry before creating a new prompt.
3. Prefer revision, suite membership, or a new variant over duplicate prompts.
4. Keep private names, secrets, personal facts, repository IDs, and inaccessible source text out of canonical prompts.
5. Preserve source lineage as a short generalized note, not copied private material.
6. Every prompt must declare a stable ID, domain, type, status, version, summary, tags, and canonical effect.
7. Separate prompt instructions from permissions, authority, tool execution, and adoption.
8. Update the registry, changelog, and tests or examples with every substantive addition.
9. Do not silently overwrite a prior prompt. Record supersession or create a versioned revision.
10. Close work with validation and exact resumption in `work/current.yaml`.
