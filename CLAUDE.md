# CLAUDE.md

## Overview

**shibc-uptime-transparency** — Public agent ops transparency page — Next.js 14 standalone. Supports CMO Proof of Autonomous Operations campaign.

> Scaffolded from `project-template` by AITO (#1268). This repo is **dormant**
> until its per-project Vault path + AppRole are provisioned out-of-band; until
> then `secrets:pull` has nothing to pull and the MCP servers stay unconnected.

## MCP servers

This repo ships a **least-privilege** `.mcp.json` (github + woodpecker + playwright for web). Additional MCP servers (directus, imagen, …) are added
deliberately and human-gated — never auto-expanded by an agent.

## Quality gates

Woodpecker CI (`.woodpecker/ci.yml`) runs typecheck + lint + tests.
