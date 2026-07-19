---
id: mp.extension.chat-to-system-prompt-harvest
title: Chat-to-System Prompt Harvest Module
domain: compounding_learning
type: router
status: candidate
version: 0.1.0
summary: An embeddable module that adds prompt harvesting and library placement to
  a broader chat-to-system workflow.
tags:
- extension
- chat-to-system
- prompt-harvest
source_lineage:
- chat-to-system practice
canonical_effect: none_until_adopted
---

# Chat-to-System Prompt Harvest Module

Add this phase after turn-local extraction and before final placement.

## Prompt harvest phase

1. Search extracted requests, corrections, strong responses, workflows, schemas, checklists, and failure analyses for reusable prompting machinery.
2. Distinguish:
   - original task prompt;
   - reusable metaprompt;
   - domain-specific commission;
   - style exemplar;
   - operational procedure better encoded as code or policy;
   - rejected prompt residue.
3. For each candidate, create a record with source locators, evidence of value, transferable job, privacy risk, overlap and disposition.
4. Generalize only after preserving the source form and lineage.
5. Route context-agnostic candidates to the metaprompt library; route ecosystem-specific commissions to their owner repository; route deterministic procedures to scripts, schemas or skills rather than prompts.
6. Update the destination registry and return a receipt with created, revised, merged, rejected and deferred candidates.

Do not delay the parent chat-to-system workflow merely to polish low-value prompts. Prioritize candidates that prevent repeated loss, drift, overreach or reinvention.
