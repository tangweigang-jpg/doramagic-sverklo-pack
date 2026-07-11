# AI Context Pack

## Pack Identity

- Upstream: https://github.com/sverklo/sverklo
- Pack type: Sverklo Codebase Memory Pack
- Doramagic canonical: https://doramagic.ai/zh/projects/sverklo/
- Relationship: independent pack; not affiliated or endorsed unless explicitly stated.

## Operating Rules

- Evidence first.
- No official endorsement claim.
- Run evals before claiming success.
- Use pitfall and risk files for recovery.

## Host Files

- `../AGENTS.md`
- `../CLAUDE.md`

## Doramagic Source Extract

# sverklo - Doramagic AI Context Pack

> Purpose: pre-work context for the user's host AI. This pack does not prove that the project has been installed, run, or validated.

## Project

- canonical_name: `sverklo/sverklo`
- capability: Repo memory for coding agents. Local-first MCP for Claude Code, Cursor, Windsurf, and Codex CLI: symbol graph, blast radius, diff-aware review, and git-pinned decisions. MIT; no API keys or code upload.
- expected_user_outcome: Repo memory for coding agents. Local-first MCP for Claude Code, Cursor, Windsurf, and Codex CLI: symbol graph, blast radius, diff-aware review, and git-pinned decisions. MIT; no API keys or code upload.

## Operating Boundaries

- Do not claim that the project has been installed, run, called through an API, or used on local files unless separate evidence proves it.
- Project facts must come from repo evidence, Claim Graph, or explicit source references.
- When a capability is not verified, mark it as unverified instead of completing it as fact.
- publish_status: `publishable`
- blocking_gaps: none

---

## Doramagic Context Augmentation

The following sections strengthen the repository context for a host AI. Human Manual data is a reading route, and pitfall notes become operating constraints.

## Human Manual Outline

Usage rule: this is only a reading route and salience signal, not factual authority. Concrete claims must still return to repo evidence or Claim Graph.

Host AI hard rules:
- Do not treat page titles, section order, summaries, or importance values as factual project evidence.
- When explaining the Human Manual outline, state that it is only a reading route or salience signal.
- Capability, installation, compatibility, runtime state, and risk claims must cite repo evidence, source paths, or Claim Graph.

- **System Overview & MCP Integration**: importance `high`
  - source_paths: README.md, package.json, src/index.ts, src/server/mcp-server.ts, bin/sverklo.ts
- **Indexer, Parsers & Language Coverage**: importance `high`
  - source_paths: src/indexer/indexer.ts, src/indexer/index-code.ts, src/indexer/index-files.ts, src/indexer/index-graph.ts, src/indexer/index-memory.ts
- **Storage, Bi-Temporal Memory & Hybrid Search**: importance `high`
  - source_paths: src/storage/database.ts, src/storage/migrations/001-initial.sql, src/storage/chunk-store.ts, src/storage/embedding-store.ts, src/storage/file-store.ts
- **CLI Workflows, Registry & Operations**: importance `high`
  - source_paths: bin/sverklo.ts, src/init.ts, src/init-global.ts, src/init-global-cli.test.ts, src/init.test.ts

## Repo Inspection Evidence

- repo_clone_verified: true
- repo_inspection_verified: true
- repo_commit: `ce4e4472529f823cf7838a9469c62258648beea5`
- inspected_files: `Dockerfile`, `README.md`, `package.json`, `docs/index-format.md`, `docs/parser-parity.md`, `docs/refactor-plan-indexer-coupling.md`, `src/init-global.test.ts`, `src/doctor.ts`, `src/init.ts`, `src/workspace.ts`, `src/init.test.ts`, `src/prove.ts`, `src/receipt.ts`, `src/init-global-cli.test.ts`, `src/prove.test.ts`, `src/modes.test.ts`, `src/workspace.test.ts`, `src/modes.ts`, `src/marketing-cli.test.ts`, `src/index.ts`

Host AI hard rules:
- Without repo_clone_verified=true, do not claim that the source code has been read.
- Without repo_inspection_verified=true, do not write README, docs, or package-file conclusions as facts.
- Without quick_start_verified=true, do not claim that the Quick Start path has run successfully.

## Doramagic Pitfall Constraints

These rules come from Doramagic discovery, validation, or compilation findings. The host AI must treat them as operating constraints, not background notes.

### Constraint 1: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: packet_text.keyword_scan | github_repo:1203034717 | https://github.com/sverklo/sverklo
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 2: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/71
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 3: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/60
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 4: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/61
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 5: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/58
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 6: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/69
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 7: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/72
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 8: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/74
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 9: Installation risk requires verification

- Trigger: Project evidence flags a installation risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: community_evidence:github | https://github.com/sverklo/sverklo/issues/73
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

### Constraint 10: Configuration risk requires verification

- Trigger: Project evidence flags a configuration risk. Review the linked source before relying on this workflow.
- Host AI rule: Reproduce the official install and quickstart path in an isolated environment.
- Why it matters: May increase setup, validation, or first-run risk for the user.
- Evidence: capability.host_targets | github_repo:1203034717 | https://github.com/sverklo/sverklo
- Hard boundary: Do not present this pitfall as solved, verified, or ignorable unless later evidence explicitly closes it.

