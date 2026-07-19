# Agents

A directory of the analysts, researchers, and specialists behind the DataForgeStudio.xyz trading intelligence platform.

Every file in this repo is a short profile for one agent: what it does, who it works alongside, and which use cases it supports. These are software agents, not people, and the bios are written that way on purpose. Where a personal detail appears, it describes how the agent was built or trained, not a human background.

## Structure

Each file is named after its agent, for example `oracle.md`, `athena.md`, `summit.md`. Every file follows the same shape:

- An avatar image (hosted in the [Avatars](https://github.com/Data-Forge-Studio/Avatars) repo)
- Name and title
- Department
- A short bio
- A "Supports" line describing what the agent contributes to

## Departments

Agents are grouped into eight functional swarms, matching the platform's own internal grouping rather than an invented structure:

- **Alpha Desk** -- crypto: market analysis, data, alerting
- **Beta Desk** -- equities: market analysis, data, alerting, fundamentals, commodities
- **Yankee Desk** -- a dedicated US-focused sub-desk
- **Gamma (Review and Oversight)** -- pre and post trade review
- **Sigma (Macro, Strategy, and Architecture)** -- the CIO's office, macro and political context, and cross-cutting strategy
- **Delta (Operations and Infrastructure)** -- the platform's own security, backups, and build pipeline
- **Pi (Prediction Markets)** -- a standalone swarm of one
- **Execution** -- paper trading, currently active on the Alpha Desk only

## Related repos

- [Use-Cases](https://github.com/Data-Forge-Studio/Use-Cases) -- which agents support which trading use case category
- [Avatars](https://github.com/Data-Forge-Studio/Avatars) -- placeholder avatar images referenced by every bio here

See [ORG-CHART.md](ORG-CHART.md) for the full reporting structure across all six departments.

## A note on scope

This repo documents who does what at a high level. It does not contain trading logic, thesis details, entry or exit rules, or portfolio data. That information is maintained privately.
