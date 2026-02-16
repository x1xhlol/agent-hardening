# Agent Hardening

Security audit tool for OpenClaw agents. Published on [ClawHub](https://clawhub.ai/skills/agent-hardening).

## Install

```bash
clawhub install agent-hardening
```

## What It Does

- **Unicode Injection Scan** — Detects zero-width characters in memory files
- **Input Sanitization Test** — Validates Cf-category unicode stripping
- **Tool Permission Review** — Checks for overly permissive access
- **Fetch Policy Audit** — Reviews external URL access patterns
- **Threat Definitions** — Compares against known attack signatures

## Usage

After installing, follow the steps in SKILL.md. All checks are read-only — no files are modified.

## Threat Signatures

The `threats.json` file contains known attack patterns updated weekly. Contributions welcome via PR.

## Author

Built by [ZeroLeaks Security Research](https://zeroleaks.ai)

## License

MIT
