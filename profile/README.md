# chaosbit.dev

Small, sharp tools from the messy middle of engineering.

Most of what lives here starts as a homelab problem: a self-hosted service that needed an
MCP server, an automation that had to be trustworthy, a pipeline that had to be fast. The
pieces that are useful beyond one house end up public.

## Public projects

| Project | What it is |
|---|---|
| [comlink](https://github.com/chaosbit-dev/comlink) | MCP server for Proton Mail via Proton Mail Bridge: search, read and organize, with guardrails on send. |
| [homeassistant-mcp](https://github.com/chaosbit-dev/homeassistant-mcp) | MCP server for Home Assistant: read states, history and cameras, control devices, and manage the registry behind fail-closed write gates. |
| [paperless-mcp](https://github.com/chaosbit-dev/paperless-mcp) | MCP server for Paperless-ngx: find documents and read their extracted fields, without returning document text. |
| [obsidian-git-mcp](https://github.com/chaosbit-dev/obsidian-git-mcp) | MCP server for an Obsidian vault kept in git: search, read, create, edit, move and delete notes, one commit per change with links kept intact. |

## How we work

- **Python first.** uv, Ruff, mypy strict, pytest. Async where it earns it.
- **Guardrails over trust.** Tools that act on your behalf get allowlists, rate limits and
  redaction, and the tests try to break them.
- **Written intent.** Designs and specs come before code and stay linked to it.

## Contact

- Writing: [chaosbit.dev](https://chaosbit.dev) ([source](https://github.com/chaosbit-dev/chaosbit.dev))
- Brand assets: [brand](https://github.com/chaosbit-dev/brand)
- Security issues: see [SECURITY.md](https://github.com/chaosbit-dev/.github/blob/main/SECURITY.md).
  Please don't open a public issue.
