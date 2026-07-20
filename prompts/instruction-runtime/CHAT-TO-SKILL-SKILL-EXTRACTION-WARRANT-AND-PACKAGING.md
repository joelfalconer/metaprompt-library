---
id: mp.instruction.chat-to-skill
title: Chat-to-SKILL.md Skill Extraction, Warrant, and Packaging
domain: instruction_runtime
type: factory
status: candidate
version: 0.1.0
summary: Mines a conversation and its artifacts for reusable operational capability, decides whether a skill is warranted, and produces validated SKILL.md packages for the correct owner and harness.
tags:
- chat-to-skill
- skill-extraction
- skill-warrant
- skill-packaging
- skills-md
- compounding
source_lineage:
- chat-to-system value extraction
- prompt-mining and library-publication factory
- cross-harness instruction architecture
canonical_effect: none_until_adopted
---

# Chat-to-SKILL.md Skill Extraction, Warrant, and Packaging

## Mission

Transform the complete accessible conversation and its associated artifacts into one or more reusable, testable, correctly placed `SKILL.md` packages when, and only when, the evidence supports a durable skill.

Do not summarize the chat and call the summary a skill. Do not generate one skill for every impressive answer. Extract recurring operational capability, preserve source lineage, distinguish skill logic from neighbouring artifact types, and produce the smallest package that another capable instance can use safely.

This prompt may run as a standalone chat-to-skill factory, as a specialized phase within a chat-to-system workflow, or against a transcript, repository history, working directory, issue thread, or mixed source estate.

## Governing transformation

```text
ephemeral conversation and artifacts
→ preserved source occurrences
→ candidate reusable procedures
→ skill-versus-non-skill adjudication
→ skill warrant
→ canonical skill design
→ harness-native SKILL.md package
→ fixtures and validation
→ owner placement and registry update
→ receipt and exact resumption
```

## Core distinctions

```text
skill ≠ prompt
skill ≠ global or repository instruction
skill ≠ policy or authority
skill ≠ agent, persona, office, or identity
skill ≠ workflow instance or current work state
skill ≠ script, tool, plugin, or MCP server
skill ≠ documentation or reference corpus
skill ≠ memory record or Golden Record
skill candidate ≠ accepted skill
skill installation ≠ permission to execute tools
canonical skill model ≠ harness-specific projection
```

A skill is a reusable package for performing a bounded class of work. It normally defines when to use the capability, what context and inputs it needs, the procedure or reasoning pattern, tool and permission boundaries, outputs, validation, failure handling, and maintenance expectations.

A reusable invocation is usually a prompt. Cross-cutting behaviour belongs in instructions. Authority belongs in policy or permissions. Deterministic transformation may belong in a script or tool. Long explanatory material belongs in documentation or references. Persistent accountability belongs to an agent, role, or office, not to a skill file.

## Inputs

```yaml
chat_to_skill_inputs:
  source_scope:
  target_repository:
  target_skill_roots: []
  target_harnesses: []
  desired_depth: minimal | standard | full
  write_authority: none | proposal_only | bounded_write
  sensitivity_exclusions: []
  existing_registry_paths: []
  branch_or_work_order:
  expected_outputs: []
```

When any input is unavailable, mark it unknown. Do not invent repository conventions, platform requirements, permissions, or source contents.

# Phase 1: Establish custody and target conventions

1. Inventory the accessible conversation, transcript, uploads, generated artifacts, sandbox files, repository files, external links, and missing or expired sources.
2. Preserve source locators for every candidate technique, correction, example, failure, and artifact.
3. Read the target repository's instructions, current work, locks, contribution rules, and existing skill registries.
4. Search all existing skill roots before proposing a new skill.
5. Inspect representative accepted `SKILL.md` files, templates, schemas, and tests.
6. Determine the target skill dialect and discovery mechanism: required directory shape, front matter, companion files, loading behaviour, tool declarations, permission model, precedence, platform version, and evidence status.
7. Identify the semantic owner, package owner, projection owner, verifier, and adoption authority.

If the target has no settled skill convention, produce a canonical candidate package plus an adapter or placement docket. Do not silently establish a repository-wide skill architecture.

# Phase 2: Mine candidate capability

Search for repeated procedures, successful reasoning sequences, user corrections, reliable tool-selection and context-loading patterns, recurring input and output contracts, validation and rollback routines, reusable checklists, strong fixtures, repeated failure modes, in-chat skills, and procedures that benefit from bundled scripts, templates, schemas, or references.

For each candidate, create:

```yaml
skill_candidate:
  id:
  title:
  source_locators: []
  recurring_job:
  trigger_hypothesis:
  non_trigger_examples: []
  inputs: []
  outputs: []
  procedure_summary:
  tools_or_resources: []
  evidence_of_value: []
  failures_prevented: []
  context_dependencies: []
  private_or_domain_specific_elements: []
  existing_skill_matches: []
  alternative_artifact_types: []
  proposed_disposition:
```

Do not generalize before source form and lineage are preserved.

# Phase 3: Apply the skill warrant

A new skill is warranted only when the candidate demonstrates most of the following:

1. **Recurrence:** the job is likely to recur.
2. **Bounded purpose:** it has one coherent responsibility and completion state.
3. **Triggerability:** another instance can tell when and when not to use it.
4. **Stable method:** the procedure is more durable than one answer or platform quirk.
5. **Input contract:** required context and prerequisites can be stated.
6. **Output contract:** expected artifacts, decisions, or mutations can be specified.
7. **Validation:** success, partial success, abstention, and failure can be tested.
8. **Context economy:** packaging saves repeated explanation without excessive loading.
9. **Safety and authority:** tools, privacy, mutation, approval, and stop conditions can be bounded.
10. **Distinctiveness:** it does not substantially duplicate an existing skill.
11. **Maintainability:** owner, version, dependencies, and review conditions can be identified.
12. **Artifact fit:** a skill is better than a prompt, instruction, policy, script, tool, workflow, documentation page, template, or Golden Record.

Score each dimension from 0 to 5 and explain the evidence. Scores support judgment; they do not replace it.

Allowed dispositions:

```text
CREATE_SKILL
REVISE_EXISTING_SKILL
EXTEND_WITH_REFERENCE_OR_FIXTURE
KEEP_AS_METAPROMPT
KEEP_AS_PROJECT_INSTRUCTION
IMPLEMENT_AS_SCRIPT_OR_TOOL
ENCODE_AS_POLICY_OR_SCHEMA
KEEP_AS_DOCUMENTATION
CAPTURE_AS_GOLDEN_RECORD
DEFER_PENDING_EVIDENCE
REJECT_NO_DURABLE_VALUE
```

If no candidate passes the warrant, return `NO_SKILL_WARRANTED` with the better destinations. That is a successful result.

# Phase 4: Design the canonical skill

For every warranted skill, define:

```yaml
canonical_skill:
  stable_id:
  name:
  slug:
  version:
  status:
  owner:
  summary:
  use_when: []
  do_not_use_when: []
  required_context: []
  optional_context: []
  inputs: []
  outputs: []
  tools: []
  permissions: []
  procedure: []
  validation: []
  failure_and_abstention: []
  privacy_and_safety: []
  dependencies: []
  companion_artifacts: []
  source_lineage: []
  supersedes: []
  review_triggers: []
```

Design rules:

- one skill per coherent reusable job;
- avoid mega-skills and trivial micro-skills;
- put critical trigger and procedure information in `SKILL.md`;
- move detailed references, examples, schemas, templates, and deterministic helpers into companion files only when they reduce core context cost;
- preserve project-local names only for intentionally project-local skills;
- state what the skill must not decide or own;
- never bury permissions or authority inside procedural prose;
- make source freshness and version-sensitive assumptions explicit.

# Phase 5: Build the SKILL.md package

Prefer the smallest package that fully supports the capability:

```text
skills/<skill-slug>/
├── SKILL.md
├── manifest.yaml            optional canonical metadata
├── references/              selected supporting material only
├── templates/               reusable output skeletons
├── examples/                positive and negative examples
├── tests/                   trigger and outcome fixtures
├── scripts/                 deterministic helpers when justified
└── CHANGELOG.md             when separately versioned
```

Do not create empty directories or ornamental files.

Adapt the native `SKILL.md` to the target dialect while preserving these semantic sections:

```markdown
# Skill name

## Purpose
## Use when
## Do not use when
## Preconditions and context loading
## Inputs
## Procedure
## Tool, permission, and mutation rules
## Outputs and filing
## Validation and done conditions
## Failure, abstention, and escalation
## Examples
## Maintenance, versioning, and supersession
```

When the native format cannot carry the canonical metadata, keep the native file compliant and place richer metadata in `manifest.yaml`. Record which fields were omitted, transformed, or approximated in the harness projection.

Create a script or tool companion only when deterministic execution materially improves reliability, speed, repeatability, or verification. Scripts need explicit inputs and outputs, dependencies, safe defaults, preview for mutations, meaningful exit status, secret and path handling, tests, and rollback or idempotency notes. A script does not gain authority merely because a skill invokes it.

# Phase 6: Validate the skill

Test at least:

1. clear positive trigger;
2. clear negative trigger;
3. ambiguous request requiring clarification or abstention;
4. missing required context;
5. unavailable tools or degraded mode;
6. provider or tool failure;
7. sensitive or restricted input;
8. conflicting repository-local instructions;
9. known strong source example;
10. known failure or correction case;
11. output structure and filing;
12. version or source-drift handling.

Evaluate trigger precision, procedure completeness, context cost, portability, tool correctness, permission and privacy boundaries, output usefulness, verification, overlap, maintainability, and retirement conditions.

Do not claim a platform accepts or auto-discovers the skill unless verified from current documentation, schema, source, or observed behaviour.

# Phase 7: Place, register, and publish

1. Produce a placement docket for every created, revised, rejected, or deferred candidate.
2. Prefer revision when an existing skill has the same identity and purpose.
3. Preserve lineage and rejected alternatives outside the concise runtime body.
4. Update the target skill registry, indexes, changelog, tests, and current work.
5. Mark the package `candidate` unless the owning authority accepts it.
6. When bounded writes are authorized, reread current state, use an isolated branch or worktree where required, write the smallest coherent package, validate, compare, commit or open a pull request, reread the published files, and record exact provider state.
7. When writes are not authorized, return complete files or a patch with exact placement instructions.

Never overwrite an accepted skill silently. Record revision, supersession, migration, or retirement.

# Required outputs

```text
SOURCE_INVENTORY
TARGET_SKILL_DIALECT
SKILL_CANDIDATE_LEDGER
SKILL_WARRANT_DECISIONS
NON_SKILL_ROUTING_LEDGER
SKILL_PACKAGE_FILES
PLACEMENT_DOCKET
REGISTRY_AND_INDEX_PATCHES
VALIDATION_REPORT
PUBLICATION_OR_PROPOSAL_RECEIPT
OPEN_QUESTIONS
EXACT_RESUMPTION
```

For each generated package, show the final file tree and identify canonical, generated, optional, and target-specific files.

# Stop conditions

Stop before publication and produce a review packet when the owner or skill root is unresolved, locks prohibit mutation, source material cannot be safely generalized, target behaviour cannot be verified, the candidate duplicates an existing skill, tool or permission boundaries are unclear, evidence is too weak, or another artifact type is a better fit.

A clean refusal to mint unnecessary capability is preferable to a library full of skill-shaped fog.
