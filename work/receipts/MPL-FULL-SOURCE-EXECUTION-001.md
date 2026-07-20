# MPL-FULL-SOURCE-EXECUTION-001 · Candidate Publication Receipt

## Result

`COMPLETE_AWAITING_EVALUATION`

## Published

- `prompts/context-continuity/FULL-SOURCE-CONTEXT-EXECUTION-AND-RESUMPTION.md`
- `registry/pending/mp.context.full-source-execution.yaml`

## Purpose

Require complete governing-prompt retrieval, current authority and lock resolution, minimum-sufficient context composition, proper system/tool routing, durable documentation and exact resumption before user handoff.

## Evaluation gate

`MPL-EVAL-001`

Test against a mature conversation, repository implementation item, private-domain item and read-only audit. Reject promotion if the prompt executes from partial retrieval, ignores active owner/lock state, writes to the wrong system or returns without durable state and exact resumption.

## Canonical effect

None until independent evaluation and owner acceptance.
