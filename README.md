# sverklo Doramagic Pack for AI Coding Agents

Pack version: `v1.0.0` · Last updated: `2026-07-11`

[![Pack v1.0.0](https://img.shields.io/badge/pack-v1.0.0-blue)](./CHANGELOG.md)
[![License](https://img.shields.io/github/license/tangweigang-jpg/doramagic-sverklo-pack)](./LICENSE)
[![Issues](https://img.shields.io/github/issues/tangweigang-jpg/doramagic-sverklo-pack)](https://github.com/tangweigang-jpg/doramagic-sverklo-pack/issues)

Languages: English | [中文](./README.zh-CN.md)

Persistent coding memory is only useful when the agent can show which files and receipts produced it.

This is an independent AI context resource pack for sverklo/sverklo: host instructions, prompt preview, evals, pitfalls, and recovery rules you can load into Claude Code, Codex, Cursor, Aider, and other AI coding agents.

> This is an independent capability pack. It is not affiliated with or endorsed by sverklo/sverklo unless explicitly stated.

## Copy / Run / Verify

1. Copy `AGENTS.md` or `CLAUDE.md` into your AI coding host.
2. Run the first prompt in `01_PROMPT_PREVIEW.md`.
3. Verify behavior with `06_EVALS/smoke_check.md`, then recover with `03_PITFALL_LOG.md` if it fails.

Quick links:
[Start](./AGENTS.md) · [Prompt](./01_PROMPT_PREVIEW.md) · [Evals](./06_EVALS/) · [Pitfalls](./03_PITFALL_LOG.md) · [Manual](./05_HUMAN_MANUAL.md)

## When This Helps

Use this pack when you want an AI coding agent to understand the upstream project context, setup boundaries, common pitfalls, and verification steps before it edits files, installs dependencies, or claims the tool is ready.

## What You Get

- Host instructions for AI coding agents.
- A copyable prompt preview.
- Acceptance checks.
- Pitfall log and recovery steps.
- Boundary and risk card.
- Human reference manual (`05_HUMAN_MANUAL.md`) with architecture, source notes, and failure taxonomy.
- Source attribution and upstream links.

If this pack helps your agent work from evidence instead of guesses, star the repo so future updates are easier to find. Open an issue for bugs, usage questions, or new pitfall reports.

## AGENTS.md for Claude Code and AI Coding Agents

Use `AGENTS.md` for agent hosts that support repository instructions. Use `CLAUDE.md` when Claude Code is the target host.

## sverklo/sverklo Pitfalls and Recovery

Start with `03_PITFALL_LOG.md` when setup, permissions, runtime behavior, or verification fails.

## Source Attribution

This project pack was assembled by [Doramagic](https://doramagic.ai) to make sverklo/sverklo usable as a portable AI capability asset.

- Upstream/source: https://github.com/sverklo/sverklo
- License: MIT
- Pack contents: prompts, host instructions, checks, guardrails, and validation notes
- Relationship: independent pack; not affiliated with or endorsed by sverklo/sverklo unless explicitly stated

If you maintain the upstream project and want attribution changed or removed, open an issue in this repository.
