# Chris Murphy

AI engineer building agent systems that run unattended: MCP servers, multi-agent tooling,
retrieval and evaluation. Before AI, 15+ years in enterprise software and manufacturing
systems (SAP ME/MII, MES, 24x7 shop-floor operations), which is where the habit of building
things that keep running comes from.

Today I lead AI adoption work at MHP Americas (a Porsche company), and I run
**Stigmergy Labs**, a small AI automation practice. Most of what's here runs on a self-hosted
platform at home: scheduled Claude agents, Postgres-backed services, and the tooling that
keeps them reviewed and deployed safely.

## Projects

| Project | What it is |
|---|---|
| [**claude-code-agent-ops**](https://github.com/cmurph1624/claude-code-agent-ops) | Guardrails for running many Claude Code sessions against real repos: an automated PR reviewer the authoring session has to answer, a registry-driven ops/deploy agent, and a hook that makes every deploy-shaped command ask a human first. |
| [**Ganglion**](https://github.com/cmurph1624/Ganglion) | Browser-based terminal multiplexer for running Claude Code sessions in parallel. Per-tab status from Claude Code hooks (working / waiting / idle), persistent shells on a server, and every session captured into a searchable memory store. |
| [**engram**](https://github.com/cmurph1624/engram) | MCP server for spaced recall: Claude runs the daily review and grades answers against rubrics, and the server handles the deterministic core (item registry, FSRS scheduling, Obsidian vault notes) with zero LLM calls. |
| [**teamreach-mcp**](https://github.com/cmurph1624/teamreach-mcp) | MCP server over TeamReach's unofficial API. It runs a 70+ player pickleball group: scheduled agents post court openings, book events weeks ahead, and alert on RSVP drop-outs by diffing snapshots. |
| [**printify-mcp**](https://github.com/cmurph1624/printify-mcp) | Fork of a Printify MCP server, hardened for real use in a print-on-demand pipeline: path sandboxing, no credential leaks, and fixes for stdio corruption, timeouts and silent failures. |

## Stack

Python, TypeScript / Node.js, Claude API and Claude Code, MCP, Postgres (pgvector), Supabase,
Docker Compose, GitHub Actions, RAG and LLM evaluation (RAGAS, Braintrust).

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/chrismmurphy)
