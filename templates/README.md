# Templates — founding forms

Copy, fill every `{{PLACEHOLDER}}`, delete the guidance comments.

These are the papers the [FOUNDING](../FOUNDING.md) walkthrough uses. The
installable suite plants a larger kit (ops jobs, MCP, skills) — that lives
in [ProtocolCity-BluePrint](https://github.com/protocolcity/ProtocolCity-BluePrint).

| Template | Copy to | As |
|---|---|---|
| [`city-AGENTS.md`](city-AGENTS.md) | **workspace** root | `AGENTS.md` |
| [`project-AGENTS.md`](project-AGENTS.md) | each **project** root | `AGENTS.md` |
| [`project-ARCHITECTURE.md`](project-ARCHITECTURE.md) | each **project** root | `ARCHITECTURE.md` |
| [`PROGRAMS.md`](PROGRAMS.md) | each **project** root | `PROGRAMS.md` |
| [`FEATURES.md`](FEATURES.md) | each project `docs/` (or root when no `docs/`) | `FEATURES.md` |
| [`BOUNDARIES.md`](BOUNDARIES.md) | workspace root (next to `AGENTS.md`) | `BOUNDARIES.md` |
| [`worker-CONTRACT.md`](worker-CONTRACT.md) | `<project>/workers/<id>/` | `CONTRACT.md` |
| [`worker-prompt.md`](worker-prompt.md) | `<project>/workers/<id>/` | `prompt.md` |
| [`vendor-pointers.md`](vendor-pointers.md) | optional | `CLAUDE.md` / `GROK.md` as thin pointers |

**Words:** workspace · project · work order · Agents · You.

A **workspace of one** may use `project-AGENTS.md` as both workspace and
project instructions until a second project exists.
