---
id: mp.architecture.entity-type-library
title: Entity-Type Library and Registry Design
domain: architecture_governance
type: crucible
status: candidate
version: 0.1.0
summary: Designs a broad option library of entity types and the admission contract for authoritative instantiated registries while preventing exploratory nouns from becoming accidental canon.
tags: [entity-types, registry, ontology, taxonomy, schema, identity]
source_lineage: [entity registry and federated taxonomy architecture]
canonical_effect: none_until_adopted
---

# Entity-Type Library and Registry Design

## Mission

Design the structures needed to discover what kinds of entities a system might model, while clearly separating candidate type options from actual registered entities.

## Required distinctions

```text
entity-type library = possible types and patterns
registry = actual instantiated identities
schema = record and validation contract
taxonomy = classification facets
ontology = classes and meaningful relations
index = pointers and discovery
catalogue = selectable examples and templates
```

Selecting a type must never instantiate an entity automatically.

## Procedure

### 1. Inventory current structures

Find existing type lists, registries, schemas, ontologies, taxonomies, indexes, naming rules and identifier systems. Record owner, revision, scope, maturity and collisions.

### 2. Define shared primitives

At minimum distinguish:

- type and instance;
- semantic entity and source occurrence;
- persistent entity, accountable office, reusable role and replaceable body;
- object, workflow, capability, implementation and tool;
- artifact, deliverable, document, representation and projection;
- stable identity, alias, path and provider ID;
- lifecycle, status, canonicality and evidence state.

### 3. Build candidate type families

Cover governance and institutions; portfolio and work; technical/runtime; knowledge/source/evidence; agents/instructions/cognition; product/design/content/commercial; creative domains; private and personal domains under additional safeguards.

### 4. Define each type

```yaml
entity_type:
  id:
  label:
  family:
  definition:
  use_when:
  do_not_use_when:
  distinguishing_features: []
  required_facets: []
  optional_facets: []
  common_relations: []
  lifecycle_pattern:
  likely_semantic_owner:
  sensitivity_considerations: []
  examples: []
  related_schema_or_registry:
  maturity: candidate
```

### 5. Define registry admission

An instantiated entity requires stable identity, semantic owner, accountable authority, evidence or accepted warrant, lifecycle and retirement condition, collision and alias review, sensitivity rules, allowed relations, canonical locator and correction/supersession behaviour.

### 6. Design federation

Specify:

- thin shared identities versus domain-owned payloads;
- index-of-indexes discovery;
- domain extension profiles;
- shared facets and ownership tuple;
- projection and adapter contracts;
- privacy-bounded references;
- migration, deprecation and alias handling;
- persistent-agent topology gate.

### 7. Validate

Use fixtures across technical systems, creative projects, research corpora, product work, agents and privacy-sensitive domains. Test duplicate types, mixed axes, noun-to-entity inflation, vendor/tool confusion, ownerless `shared`, and accidental private-data centralization.

## Required outputs

- source inventory and collision report;
- entity-type library schema and library;
- type/instance/occurrence/role/body matrix;
- registry admission contract;
- common facet and relation model;
- index-of-indexes architecture;
- domain extension guide;
- migration and deprecation rules;
- validation fixtures;
- owner and adoption docket.

## Stop conditions

Stop before creating or migrating registry records when owner, warrant, identity, sensitivity or admission rules are unresolved. Return candidate types and a review packet only.
