# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability, please report it privately.

**Do not open a public issue.**

Email: us@runlegion.dev

Include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

## Response Time

We aim to respond within 48 hours and provide a fix within 7 days for critical issues.

## Scope

Legion runs locally on your machines. The primary attack surface is:
- The CLI binary itself
- The SQLite database (reflection/task data)
- The dashboard web UI (served locally)
- The plugin system (hooks, channel)

If you find a way to escalate from any of these, we want to know.
