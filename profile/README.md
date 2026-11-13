<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alpine-Ronin/.github/main/profile/logo-dark.svg">
    <img src="https://raw.githubusercontent.com/Alpine-Ronin/.github/main/profile/logo.svg" alt="Alpine Ronin" width="380">
  </picture>
</p>

<p align="center">
  <strong>Coding with AI agents, safely.</strong><br>
  Open source MCP servers that give coding agents what they need to know, and only what they are allowed to do.
</p>

---

Agents write code fast. They also run commands they should not, guess at code they have not read and walk past the
architecture a team agreed on. Alpine Ronin builds the guardrails that sit between the agent and the project:
deterministic, local, and working with any MCP client (Claude Code, Codex, Cursor and others).

## Projects

| | |
|---|---|
| [**Airlock**](https://github.com/Alpine-Ronin/airlock) | Every agent command passes through it. An MCP server that lets any agent run shell commands on your machine, without trusting the agent with your machine. |
| [**phpgraph**](https://github.com/Alpine-Ronin/phpgraph) | A knowledge graph of your PHP codebase, for AI coding agents. Static analysis over MCP: no LLM, no network, no embeddings, deterministic facts with a confidence level each. |
| **Architecture guardrails** *(coming soon)* | An MCP server that holds agents to your architecture: layers, boundaries and dependency rules checked before the change lands, not in review. |

## Principles

- **Deterministic.** Facts and rules, not guesses. When something is inferred, it says so.
- **Local.** Your code stays on your machine.
- **Agent-agnostic.** Built on MCP, so it works with the agent you already use.

## The name

A summit crossed by a blade. *Alpine* for the climb: guiding agents through code they do not know. *Ronin* for the
independence: small, sharp tools, beholden to no single vendor.

<p align="center"><sub>Built by <a href="https://github.com/hbenabdallah">Houssem Ben Abdallah</a> · MIT licensed</sub></p>
