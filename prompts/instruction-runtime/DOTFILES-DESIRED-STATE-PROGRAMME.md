---
id: mp.instruction.dotfiles-programme
title: Dotfiles Desired-State Programme
domain: instruction_runtime
type: commission
status: candidate
version: 0.1.0
summary: Converts captured user configuration into reviewed, secret-safe, cross-platform
  desired state with templating, validation and rollback.
tags:
- dotfiles
- desired-state
- secrets
- cross-platform
source_lineage:
- runtime fabric dotfiles programme
canonical_effect: none_until_adopted
---

# Dotfiles Desired-State Programme

## Mission

Turn a captured configuration repository into a reviewed desired-state system. The current live files are evidence, not automatic canon.

## Required sequence

1. inventory paths, history, backups, generated state, secrets, absolute bindings and configuration precedence;
2. classify keep, template, split, regenerate, archive, ignore or delete-candidate;
3. define one source with platform and host overlays;
4. integrate a secret manager by reference, never plaintext;
5. define package/runtime responsibility among OS managers, language/tool managers and project-local environments;
6. create Windows, Linux/WSL and server fixtures;
7. preview diffs before apply;
8. verify effective configuration and rollback on disposable targets;
9. publish migration ledger and drift receipts;
10. mutate live user configuration only through a separately approved work order.

Reject whole-profile capture and vendor-cache mirroring as desired state.
