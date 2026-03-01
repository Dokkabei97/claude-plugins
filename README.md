# Dokkabei Plugins for Claude Code

A unified plugin marketplace for Claude Code by [Dokkabei97](https://github.com/Dokkabei97).

## Quick Start

```bash
# Add marketplace (one-time)
/plugin marketplace add Dokkabei97/claude-plugins

# Install plugins
/plugin install all-agents-mcp
/plugin install hardened-claude-code
/plugin install forged-claude-code
```

## Available Plugins

### all-agents-mcp

Orchestrate multiple AI CLI agents (Claude Code, Codex, Gemini CLI, Copilot CLI) through a unified MCP interface.

- 13 MCP tools + 6 skills + 2 commands
- Single/multi-agent queries, task delegation, cross-model verification
- Safe by design — direct CLI invocation, no OAuth token hijacking

[Repository](https://github.com/Dokkabei97/all-agents-mcp)

### hardened-claude-code

Production-hardened Claude Code configuration for enterprise-scale systems with safety hooks and multi-stack support.

- 4 agents (arch-reviewer, perf-reviewer, e2e-runner, tdd-guide)
- 9 commands (analyze, arch-review, tdd, e2e, and more)
- 7 skills (sync-claude-md, flow-scaffolding, obsidian-tech-note, and more)
- Safety hooks for Kotlin, TypeScript, and Python development

[Repository](https://github.com/Dokkabei97/hardened-claude-code)

### forged-claude-code

Startup founding & operations toolkit covering the full startup lifecycle from MVP to growth.

- 9 agents (tech-stack-advisor, security-audit, cost-optimizer, ux-reviewer, and more)
- 14 commands (rapid-prototype, runway-calculator, value-proposition, and more)
- 29 skills across 4 C-level domains (CTO, CPO, COO, CMO)
- Secret scanner hook for preventing credential leaks
- 3-phase implementation roadmap (Foundation → Build & Launch → Growth)

[Repository](https://github.com/Dokkabei97/forged-claude-code)

## Plugin Comparison

| | hardened-claude-code | forged-claude-code |
|---|---|---|
| **Focus** | Enterprise engineering | Startup operations |
| **Plugins** | 20 (code quality) | 53 (full business stack) |
| **Domains** | Engineering | CTO + CPO + COO + CMO |

## License

MIT
