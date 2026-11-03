<div align="center">

# OYYO Catalogs

### Independent content for the OYYO workspace.

**536 roles · 50 team presets · 1,361 tasks · 204 creative styles**

**Available for private demos and private beta. [Request early access](https://oyyo.one/contact).**

</div>

This repository publishes versioned role, team, task and creative-style content independently from application releases. The current catalog extends the built-in definitions with 336 nested delivery/validation roles, 50 specialist team presets, 1,136 task entries and 192 visual directions. Combined totals are 536 roles, 1,361 tasks and 204 styles, with seven built-in workflow groups plus the 50 presets.

Task additions cover scope/evidence briefs, finished deliverables, review checklists and execution/handoff plans for each of the 536 workspace roles. Creative directions are grouped into 24 additional visual families. A creative style is a direction for a brief, not a generated preview or a model release.

## Catalog identity

- Catalog version: **2026.11.03.3**.
- `library.json` describes the versioned content file, byte count and SHA-256.
- `content/` contains the corresponding content snapshots.
- Content updates do not require a new app build once catalog-sync support is present.

## Synchronisation

The workspace's **Task library → Sync catalog** control fetches the official manifest and content snapshot. It checks the supported schema, expected source, size, integrity, unique IDs, known role/workflow references and allowed fields before replacing its cached catalog. It does not download executable plugins or grant new tool permissions. The last accepted library remains available locally if a later sync fails or the machine is offline.

Sync is manual. Existing app builds without catalog-sync support need a compatible application update first. The current sync scope is **task templates, creative styles, role definitions and team presets**; it does not install models, create new executable tools or alter agent/runtime implementation. Model and agent catalogs retain their own capability and qualification requirements.

SHA-256 verifies consistency with the manifest; it is not an independent digital signature or a benchmark score.

## Explore the catalogs

| Repository | Purpose |
| --- | --- |
| [OYYO Task Library](https://github.com/vpicciuolo/oyyo-task-library) | Human-readable task index, departments and creative-style descriptions |
| [OYYO Agents](https://github.com/vpicciuolo/oyyo-agents) | 536 specialist role names and responsibilities |
| [OYYO Teams](https://github.com/vpicciuolo/oyyo-teams) | Seven built-in workflow groups and collaboration guides |
| [OYYO Models](https://github.com/vpicciuolo/oyyo-models) | Model lineup, capabilities and requirements |

OYYO is proprietary technology. This repository describes catalog content; it does not publish the private orchestration engine or grant rights to private product implementation. Required third-party rights and notices remain applicable.

**Copyright © 2026 OYYO · HRN INNOVATION TECHNOLOGIES LTD. All rights reserved.**

## Main OYYO documentation

[OYYO ONE AI documentation hub](https://github.com/vpicciuolo/oyyo-one-ai) · [OYYO website](https://oyyo.one) · [Exclusive preview](https://oyyo.one/contact)

