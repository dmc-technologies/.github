# Architecture

This repository holds the organization defaults GitHub applies to every dmc-technologies repository.

| Path | What it owns |
| --- | --- |
| `PULL_REQUEST_TEMPLATE.md` | The default pull request description for every repository without its own template |
| `README.md` | What this repository is for |
| `AGENTS.md` | Instructions for agents working in this repository, starting with the DMC review policy block |
| `.github/agent-accounts` | The GitHub logins that belong to agents |
| `.github/workflows/ci.yml` | The required `CI` check: a gitleaks scan of the full history |
