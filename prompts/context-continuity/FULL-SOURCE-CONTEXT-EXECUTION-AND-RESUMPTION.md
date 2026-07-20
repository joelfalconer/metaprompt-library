# Full-Source Context Execution and Resumption

## Purpose

Recover the complete governing prompt and source context before executing a work item, route the work to the correct owner and tool surface, maintain durable documentation and project-management mirrors, and return an exact resumption state.

## Inputs

```text
WORK ITEM ID OR CODE:
{{WORK_ITEM_ID_OR_CODE}}

WORK ITEM NAME:
{{WORK_ITEM_NAME_OR_UNKNOWN}}

OPTIONAL OPERATOR NOTE:
{{OPTIONAL_OPERATOR_NOTE_OR_NONE}}

SOURCE PROMPT, FILE, CHAT, ISSUE OR CONTEXT-PACK LOCATOR:
{{LOCATOR_OR_UNKNOWN}}
```

## Prompt

```text
Treat the supplied fields as locators, not as a complete commission or mutation authority.

1. Recover the complete governing prompt. Search the relevant file/conversation estate, then read the full contiguous prompt and every operative referenced source. Follow pagination and continuation markers. Never execute from snippets, memory, filenames or partial quotes. Record source IDs, versions, ranges, missing segments and whether execution is safe.
2. Resolve current authority and live state. Read the governing repository, active Work Order, current state, locks, branches, receipts and provider objects before relying on issues, dashboards or historical chat. Classify claims as live verified, implemented-unverified, accepted architecture, active, queued, blocked, candidate, donor, superseded, stale or unknown.
3. Detect overlap. Check active workers, max-length chats, abandoned branches, duplicate issues, newer decisions and better-context owner instances. Route back rather than parallelising when another instance owns the work.
4. Compose the minimum sufficient context pack: objective, non-goals, owner, authority, revision, selected/excluded sources, lineage, decisions, questions, dependencies, blockers, locks, sensitivity, allowed tools, mutation scope, prohibited actions, validation, rollback, deliverables, acceptance, return destination and exact resumption.
5. Use systems by function: files for source recovery; repositories for versioned truth; issue trackers for delivery mirrors; knowledge workspaces for human orientation; drives for source/media/collaboration/delivery; task managers for immediate human actions; calendars for scheduled commitments; email for communication; source systems for provenance; architecture systems for topology and ownership; runtimes for durable execution; machine systems for desired/observed environment state.
6. Choose one route: continue here, return to existing instance, start a specialist instance, run in a local harness, owner review only, wait for dependency, defer, retire or no work warranted.
7. Before consequential work, emit a Prompt Recovery Receipt and Execution Docket. Stop when the prompt is incomplete, authority unresolved, a predecessor unfinished, an exclusive lock exists, privacy policy is absent or rollback is undefined.
8. Execute only the bounded outcome. Preserve corrections, rejected variants, contradictions, negative evidence and lineage. Do not treat generated prose, files, branches or issues as completion without owner-defined validation.
9. Before returning, update the smallest authoritative set required, then update project-management and orientation mirrors only when their state changed. Reread every external write and record exact revisions and failures.
10. Validate tests, schemas, builds, provider state and human gates. Distinguish attempted, generated, written, published, applied, observed, verified and accepted.
11. Close with exactly one explicit result and a receipt containing work performed, source revisions, files/provider objects changed, validation, incomplete work, risk, rollback, next item, next context pack, next owner and first resumption action.
12. The final user handoff must state what changed, what did not, honest completion state, links, next-action queue, operator decisions and exact next prompt input. Leave the work runnable.
```

## Evaluation requirements

Test against at least one mature conversation, one repository implementation item, one private-domain item and one read-only audit. Fail the prompt when it executes from partial file retrieval, ignores a live owner/lock, writes to the wrong system, or returns without durable state and exact resumption.
