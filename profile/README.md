# Agent Quality Controls

**Deterministic quality controls for code and prose written by AI agents.**

AI agents produce code and writing faster than humans. Speed creates volume; volume creates defects. Agent Quality Controls is a suite of deterministic, LLM-free tools that catch defects at the point of production - before they enter a codebase, a release, or a published draft.

The tools share three principles:

- **Deterministic.** No LLM in the loop. Same input, same output, every time.
- **Banned by default.** What the tool permits is explicit. Everything else is a finding.
- **Self-validating.** Each tool runs its own rules against itself.

## Tools

| Tool | What it checks |
|---|---|
| [guardrail3](https://github.com/agent-quality-controls/guardrail3) | Code guardrails for Rust and TypeScript: banned APIs, architectural topology, input validation, centralized I/O, total lint-suppression visibility |
| [fixture3](https://github.com/agent-quality-controls/fixture3) | Fixture-based approval testing CLI for agent-managed codebases |
| [slopless](https://github.com/agent-quality-controls/slopless) | Deterministic Markdown linter for AI and human prose slop - 50+ rules across metrics, orthography, phrases, syntactic patterns, and semantic thinness |

## Status

Pre-1.0. APIs and rule taxonomies will change. Issues and discussions welcome on each repo.
