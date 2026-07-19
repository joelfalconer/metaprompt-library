---
id: mp.instruction.architecture-research
title: System Instruction Architecture Research Programme
domain: instruction_runtime
type: research_programme
status: candidate
version: 0.1.0
summary: Investigates where instructions, personalization, memory, agent rules, skills,
  hooks and enforcement belong across platforms and scopes.
tags:
- instructions
- personalization
- agents-md
- skills
- cross-harness
source_lineage:
- deep research instruction architecture programme
canonical_effect: none_until_adopted
---

# System Instruction Architecture Research Programme

## Mission

Conduct a current, implementation-oriented investigation into the design, prioritization, versioning, testing, deployment and continuous improvement of instruction layers across consumer personalization, APIs, workspaces, repositories, agents, skills, memory, hooks and deterministic controls.

## Core question

```text
constitution → user profile → organisation → workspace → project → repository
→ directory → agent → capability → workflow → task → tool → artifact
```

Which information belongs at each layer, what is its precedence and persistence, and which high-consequence invariants must be enforced by permissions, schemas, linters, tests, sandboxes, approvals or CI rather than only requested in prose?

## Requirements

- temporal and version ledger for every platform;
- primary-source hierarchy and evidence labels;
- platform instruction atlas;
- length and context-budget analysis;
- vendor-neutral canonical schema;
- adapter and degraded-mode rules;
- preflight and postflight hooks;
- versioning, migration, supersession and rollback;
- evaluation and ablation suite;
- privacy and supply-chain threat model;
- compounding loop for corrections and golden outcomes.

Do not assume longer files improve performance or that a harness is the canonical database.
