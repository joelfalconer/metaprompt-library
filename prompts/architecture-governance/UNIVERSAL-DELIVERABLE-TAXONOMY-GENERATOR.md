---
id: mp.architecture.deliverable-taxonomy
title: Universal Deliverable Taxonomy Generator
domain: architecture_governance
type: compiler
status: candidate
version: 0.1.0
summary: Builds a broad, typed and extensible library of possible project deliverables without making every option mandatory for every project.
tags: [deliverable-taxonomy, documentation, project-types, registry, ontology]
source_lineage: [project deliverable architecture practice]
canonical_effect: none_until_adopted
---

# Universal Deliverable Taxonomy Generator

## Mission

Create or revise an expansive library of deliverable **types** from which project-specific selection can occur.

The output is an option space, not a project checklist and not a registry of completed artifacts.

## Required distinctions

```text
deliverable type ≠ deliverable instance
artifact ≠ deliverable ≠ provider object
working document ≠ accepted contract ≠ generated projection
category ≠ lifecycle ≠ format ≠ audience ≠ owner
```

## Procedure

1. Inventory deliverable terminology from representative project classes, existing libraries, standards and source materials.
2. Normalize aliases while preserving useful distinctions.
3. Organize types into coherent families such as:
   - orientation and boundary;
   - discovery and research;
   - strategy, product and business;
   - requirements and specification;
   - architecture and engineering;
   - data, knowledge and semantics;
   - design, brand and experience;
   - creative, editorial and knowledge-vault work;
   - marketing, growth and commercial;
   - programme, operations and governance;
   - quality, security, legal and release;
   - AI, agent, instruction and runtime systems.
4. For each type define:

```yaml
deliverable_type:
  id:
  label:
  definition:
  family:
  purpose:
  use_when:
  do_not_use_when:
  typical_audiences: []
  likely_owner:
  prerequisites: []
  related_types: []
  lifecycle:
  common_formats: []
  canonicality_pattern:
  validation_patterns: []
  maintenance_or_retirement:
  aliases: []
  maturity: candidate
```

5. Create project-profile defaults that select required, recommended and conditional types for different project classes.
6. Add extension rules so domains can define specialised types without copying or forking the core library.
7. Test for duplicate concepts, mixed axes, vendor-specific types, output-format masquerading as purpose, and types with no decision function.
8. Produce machine-readable registry, human navigation, alias map, profile matrix, schema and validation fixtures.

## Coverage tests

Demonstrate selection for at least:

- web or software application;
- library or package;
- platform or monorepo;
- data or AI system;
- agent or harness system;
- infrastructure runtime;
- Obsidian vault or knowledge framework;
- brand identity;
- marketing strategy or campaign;
- creative/worldbuilding project;
- research programme;
- institution or operating system;
- migration or refactor;
- template or asset collection.

## Quality gates

- identifiers remain stable and non-vendor-specific;
- every type has a decision function, owner pattern, lifecycle and validation path;
- profiles remain selective rather than exhaustive;
- format is represented as a facet unless the format itself defines the deliverable's function;
- the library does not claim that deliverable instances exist;
- domain extensions and supersession are explicit.

## Stop conditions

Stop before canonization when project coverage, ownership, extension or deprecation rules remain unresolved. Publish a candidate library and evaluation plan instead.
