---
id: mp.factory.prompt-mining-publication
title: Prompt Mining and Library Publication Factory
domain: compounding_learning
type: factory
status: candidate
version: 0.1.0
summary: Mines chats and working files for reusable prompt systems, generalizes and
  tests them, places them in this repository, updates registries, and publishes a
  verified commit.
tags:
- factory
- prompt-mining
- repository-publication
- chat-to-system
- compounding
source_lineage:
- chat-to-system reconstruction practice
- prompt evaluation and taxonomy review
canonical_effect: none_until_adopted
---

# Prompt Mining and Library Publication Factory

## Mission

Inspect the full available conversation, attached files, generated sandbox artifacts, and the current metaprompt-library repository. Identify prompts, prompt fragments, workflows, evaluation rubrics, extraction procedures, and repeated operator corrections that deserve durable context-agnostic forms.

Do not treat every user request as a reusable prompt. Mine for **repeatable cognitive machinery**.

## Inputs

- conversation or transcript scope;
- accessible sandbox or working-directory scope;
- repository URL or local checkout;
- mutation authority and branch policy;
- sensitivity exclusions;
- desired output depth.

## Procedure

### 1. Establish custody and current state

1. Read repository instructions, taxonomy, registry, work state, and active locks.
2. Inventory accessible conversation, files, archives, generated artifacts, and existing prompts.
3. Record inaccessible or expired sources. Never invent their contents.
4. Hash or otherwise identify source representations when exact lineage matters.

### 2. Detect candidates

Look for:

- prompts that produced unusually strong results;
- in-chat metaprompts or multi-stage task programmes;
- repeated user corrections that reveal a better general procedure;
- successful handoff, extraction, review, placement, or research formats;
- prompts that should have existed to prevent a failure;
- recurring work presently performed manually across chats;
- complementary prompts that form a suite.

For each candidate record:

```yaml
candidate:
  title:
  source_locator:
  original_job:
  reusable_job:
  evidence_of_value:
  failure_prevented:
  domain_specific_elements:
  privacy_risk:
  overlaps: []
  recommended_action: extract | merge | revise | suite | reject
```

### 3. Score candidates

Score 0–5 for recurrence, transferability, outcome value, procedural clarity, evaluability, safety, distinctiveness, and durability. Reject candidates that are merely eloquent, one-off, private, or dependent on hidden context.

### 4. Generalize without bleaching

- Replace proper nouns with typed placeholders.
- Preserve the operative distinctions, constraints, gates, schemas, and quality checks.
- Separate generic method from domain examples.
- Keep tool usage optional unless the prompt's purpose is tool-governed execution.
- Preserve rejected variants and source notes outside the canonical prompt body.

### 5. Adversarially review

Test for:

- duplicate library coverage;
- category, role, tool, and owner confusion;
- missing input or output contracts;
- authority overreach;
- privacy leakage;
- claims of work not actually performed;
- inability to stop or abstain;
- instructions that reward verbosity rather than completion;
- hidden dependency on one platform.

### 6. Place and package

1. Search `registry/prompts.yaml` and `registry/taxonomy.yaml`.
2. Revise an existing prompt when the reusable job is substantially the same.
3. Create a new prompt only when it has a distinct job and stable identity.
4. Create or update a suite when several prompts form a deliberate sequence.
5. Add source-lineage notes, examples, tests, and registry metadata.
6. Update `CHANGELOG.md` and `work/current.yaml`.

### 7. Publish

When repository writes are authorised:

```text
reread remote head
→ create isolated branch
→ write smallest coherent patch
→ validate paths, metadata and registry references
→ compare branch with current default branch
→ open PR or fast-forward according to repository policy
→ reread published files
→ record commit, validation and exact resumption
```

Never force-push, rewrite unrelated work, or claim publication without a verified provider result.

## Required outputs

- source and candidate inventory;
- extraction and rejection ledger;
- new or revised prompt files;
- updated prompt and suite registries;
- validation report;
- publication receipt;
- exact next prompt or work item.

## Stop conditions

Stop before mutation when repository state, authority, privacy, or placement is unresolved. Produce a review packet instead.
