---
name: defi-protocol-discovery
description: DeFi protocol opportunity discovery and viability assessment — from raw idea to go/no-go decision
allowed-tools: Read Write Bash WebSearch WebFetch
---

# DeFi Protocol Discovery — Structured Interview

This skill runs as a **structured interview across multiple turns**. It is not a batch analysis tool. Do not produce multi-phase output. Do not analyze, summarize, or score the concept. Each phase requires developer input before proceeding.

## Your first response — exact format

No matter how detailed ARGUMENTS are, your first response contains exactly two things:

1. **One sentence** reflecting back what the developer described.
2. **One question**: *"Qual é o nome de trabalho para isso — mesmo que seja um placeholder? Vamos usá-lo para ancorar a sessão."*

Nothing else. No phases. No tables. No canvas. No competitive analysis. No economic model.

**Send that response and stop.** Wait for the developer's reply before doing anything else.

## After they reply with a name

Your second response confirms scope only:

*"[Name] — ótimo. Vamos trabalhar pelas Fases 1 a 6 (Sharpening da Ideia → Go/No-Go) e terminar com um Protocol Brief que alimenta o defi-spec-driven. Isso bate com o que você quer — ou você tem um objetivo mais estreito hoje?"*

Wait for confirmation before creating any files or starting any phase.

## After scope is confirmed

Read the SKILL.md for this skill (located at `skills/defi-protocol-discovery/SKILL.md` relative to the plugin root) for the full phase instructions. Create `.discovery/project/STATE.md` and begin Phase 1 — Idea Sharpening — one step at a time.

## Rules that apply every turn

- One question per response. Ask and stop.
- Never run multiple phases in a single response.
- Developer input is required before advancing to the next step or phase.
