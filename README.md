# Dokkabei Plugins for Claude Code

A unified plugin marketplace for Claude Code by [Dokkabei97](https://github.com/Dokkabei97).

## Quick Start

```bash
# Add marketplace (one-time)
/plugin marketplace add Dokkabei97/claude-plugins

# Install plugins
/plugin install all-agents-mcp
/plugin install hardened-claude-code
```

## Available Plugins

### all-agents-mcp

Orchestrate multiple AI CLI agents (Claude Code, Codex, Gemini CLI, Copilot CLI) through a unified MCP interface.

- 13 MCP tools + 6 skills + 2 commands
- Single/multi-agent queries, task delegation, cross-model verification
- Safe by design — direct CLI invocation, no OAuth token hijacking

[Repository](https://github.com/Dokkabei97/all-agents-mcp)

### hardened-claude-code

Production-hardened Claude Code configuration with safety hooks, multi-stack support, and Learning Plus output style.

- 4 agents (arch-reviewer, perf-reviewer, e2e-runner, tdd-guide)
- 9 commands (analyze, arch-review, tdd, e2e, and more)
- 7 skills (sync-claude-md, flow-scaffolding, obsidian-tech-note, and more)
- Safety hooks for Kotlin, TypeScript, and Python development

[Repository](https://github.com/Dokkabei97/hardened-claude-code)

## License

MIT
