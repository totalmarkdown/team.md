# TEAM.md

> *Defines how multiple AI agents coordinate, share context, and collaborate on tasks*

[![License: CC0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
[![Part of agent-md-specs](https://img.shields.io/badge/part%20of-agent--md--specs-blue)](https://github.com/totalmarkdown/agent-md-specs)
[![Maintained by TotalMarkdown](https://img.shields.io/badge/maintained%20by-TotalMarkdown.ai-8B5CF6)](https://totalmarkdown.ai)

**Maintained by TotalMarkdown.ai**
· License: CC0 1.0 Universal — Public Domain
· Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
· [Discussions](https://github.com/totalmarkdown/team.md/discussions)

> TotalMarkdown.ai is currently in development. Star this repo to follow progress.

---

## What is TEAM.md?

TEAM.md defines the structure and protocols for multi-agent collaboration. When you need two or more AI agents to work together on a task, TEAM.md specifies who does what, how they communicate, and how they resolve conflicts.

Without a team configuration, multi-agent systems devolve into chaos — agents duplicate work, contradict each other, or drop tasks entirely. TEAM.md prevents this by declaring roles, communication channels, and decision-making authority upfront.

Use TEAM.md any time you're orchestrating agents that need to share state, hand off work, or coordinate on a single deliverable.

---

## Quick Start

```bash
curl -O https://raw.githubusercontent.com/totalmarkdown/team.md/main/TEAM.md
```

Add to your project root and customize for your agent.

---

## When to use TEAM.md

- Coordinating a code review pipeline where one agent writes code, another reviews, and a third runs tests
- Setting up a research team where agents divide topics, share findings, and synthesize results
- Defining handoff protocols between a customer-facing agent and a specialist agent

---

## Where it fits

Works alongside SOUL.md (individual agent identity), ESCALATION.md (when to involve humans), and SWARM.md (large-scale agent coordination). Referenced by AGENTS.md and CLAUDE.md as the standard for multi-agent setups.

---

## The Full Spec

→ [TEAM.md](./TEAM.md)

---

## Part of agent-md-specs

One of 174 specs in [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)
— the open standard library covering every dimension of AI agent configuration.

---

## Contributing

1. Open an issue describing your proposed change
2. Fork and make your edit
3. Open a PR — all contributions must be CC0

---

## License

[CC0 1.0 Universal](./LICENSE) — Public Domain.
Use freely for any purpose, no attribution required.

---

*Maintained by TotalMarkdown.ai*
*Part of [agent-md-specs](https://github.com/totalmarkdown/agent-md-specs)*
