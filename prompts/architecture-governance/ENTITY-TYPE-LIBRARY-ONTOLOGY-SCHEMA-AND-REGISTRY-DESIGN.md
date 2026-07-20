# Entity-Type Library, Ontology, Schema and Registry Design

```text
Design the semantic structures needed to model a project or ecosystem without turning every possible noun into an instantiated entity.

First distinguish:
- entity-type library: candidate kinds of things that may be modelled;
- taxonomy: classification facets;
- ontology: meaningful classes and relationships;
- schema: fields, constraints and validation;
- registry: authoritative records of actual entities;
- index: pointers to registries and records;
- catalogue: selectable patterns, templates and examples.

1. Inventory the domain, use cases, existing records, registries, schemas, identifiers and naming conventions.
2. Identify candidate entity families and distinguishing features. Search existing types and owners before proposing new ones.
3. For each candidate type define:
   - stable candidate ID and label;
   - definition, use when and do not use when;
   - required and optional facets;
   - common relations;
   - identity and lifecycle pattern;
   - likely semantic owner;
   - sensitivity considerations;
   - examples and counterexamples;
   - related schema or registry;
   - maturity and deprecation state.
4. Define common cross-domain facets and domain extension rules. Avoid a universal schema that absorbs owner-local meaning.
5. Design registry admission. An actual entity requires distinct identity, evidence or creation warrant, owner and authority, lifecycle and retirement, scope and non-goals, sensitivity and disclosure, collision review and canonical locator.
6. Define alias, merge, split, correction, supersession and deprecation procedures.
7. Specify the index-of-indexes and discovery path without centralising private payload.
8. Create validation fixtures for false merges, attractive-but-empty entity names, tool-as-capability errors, vendor-as-platform errors, ownerless shared records and persistent-agent creation without accountability.
9. Produce project-specific mappings only as candidates until the relevant owner accepts them.

Return:
A. semantic-structure distinction and boundary;
B. nested candidate entity-type library;
C. taxonomy and common facets;
D. ontology and relation model;
E. schema and registry responsibilities;
F. registry admission and lifecycle gate;
G. index-of-indexes design;
H. extension, alias, merge and supersession rules;
I. validation fixtures;
J. unresolved owner decisions.

Do not instantiate entities, mint stable identities or promote agents merely because the library contains a type.
```
