---
id: mp.architecture.project-deliverable-selection
title: Project Deliverable Architecture and Selection
domain: architecture_governance
type: crucible
status: candidate
version: 0.1.0
summary: Selects the smallest coherent, project-specific set of deliverables from a broad option library and sequences their creation, ownership and maintenance.
tags: [deliverables, project-planning, documentation-architecture, selection, roadmap]
source_lineage: [repeated project deliverable planning prompts]
canonical_effect: none_until_adopted
---

# Project Deliverable Architecture and Selection

## Mission

Determine which documents, models, schemas, plans, prototypes, registries, operating records and delivery artifacts a project actually needs.

Do not merely expand the user's examples into a longer checklist. Infer the project's type, lifecycle, consequence and operating reality, then select a coherent deliverable architecture.

## Inputs

- project or system description;
- project types and lifecycle stage;
- intended users, operators and stakeholders;
- existing sources and deliverables;
- technical, creative, commercial and governance boundaries;
- team, toolchain and repository state;
- delivery, maintenance and retirement expectations.

## Procedure

### 1. Classify the project

Use multiple profiles when appropriate: software, package, platform, data/AI, agent or harness, infrastructure, knowledge vault, brand, campaign, creative work, research programme, institution, migration/refactor or content/template collection.

### 2. Establish selection factors

Evaluate:

- greenfield, brownfield or mixed;
- discovery, definition, build, migration, operation or retirement stage;
- consequence and reversibility;
- team and stakeholder complexity;
- public/private and regulatory exposure;
- technical and semantic complexity;
- expected operating lifetime;
- need for external delivery, collaboration or audit.

### 3. Inventory existing coverage

Map current artifacts against deliverable functions. Mark current, stale, incomplete, duplicated, donor, generated, accepted or missing. Do not recommend a new document when an existing canonical file can be revised.

### 4. Select by decision function

For each candidate deliverable, require:

- decision, action or user enabled;
- owner and audience;
- canonical destination;
- prerequisites;
- lifecycle stage;
- validation and acceptance;
- maintenance or retirement path;
- relation to other deliverables.

Classify each as:

```text
required now
required before a named gate
recommended
conditional
supplied by another owner
generated projection
donor only
not applicable
```

### 5. Cover the necessary families

Review orientation; discovery and research; strategy and product; requirements and specification; architecture and engineering; data and semantics; design and brand; creative/editorial; marketing and commercial; programme operations; quality/security/legal; release/adoption/lifecycle; agent and instruction systems; knowledge-vault frameworks.

### 6. Sequence delivery

Build a dependency-aware order. Prefer thin early artifacts that unlock decisions, then deepen only where consequence and implementation require it. Separate working documents, accepted contracts, generated projections and provider-native mirrors.

### 7. Produce the deliverable architecture

```yaml
project_deliverable_architecture:
  project_types: []
  lifecycle_stage:
  selection_factors: {}
  existing_coverage: []
  selected:
    - deliverable_type:
      status:
      purpose:
      audience: []
      owner:
      canonical_destination:
      prerequisites: []
      validation: []
      maintenance_or_retirement:
  supplied_by_other_owners: []
  generated_projections: []
  duplicates_or_rejections: []
  dependency_sequence: []
  immediate_minimum_set: []
  later_gate_sets: []
  unresolved_questions: []
```

## Quality gates

Reject deliverables that lack a user, decision function, owner, validation or maintenance story. Flag conflicting sources of truth. Explain why each selected deliverable exists and why notable candidates were omitted.

## Stop conditions

Stop before inventing project architecture when the project itself, its owner, current stage or existing artifact estate cannot be established. Return the missing-context docket first.
