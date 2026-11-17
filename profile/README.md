# Jig

A framework for building software with an AI coding agent — Claude Code or Codex.

You describe what you want in plain words; the agent sizes the work by its risk,
keeps the project's knowledge up to date, and stops to ask you where a human
decision matters. A typo is fixed in three steps; a change to authentication is
designed, approved by you and independently reviewed.

Jig lives inside your project: a folder of project knowledge committed with the
code, skills your agent follows, and a small shell tool the agent runs for the
mechanical parts. Nothing is hosted, there is no telemetry, and no script ever
calls an AI model. MIT-licensed.

macOS and Linux:

```bash
curl -fsSL https://raw.githubusercontent.com/fapost-jig/jig/main/install.sh | bash
```

Windows, in PowerShell:

```powershell
irm https://raw.githubusercontent.com/fapost-jig/jig/main/install.ps1 | iex
```

**[Documentation](https://jig.fapost.in)** · **[Changelog](https://jig.fapost.in/changelog)** · **[Roadmap](https://jig.fapost.in/roadmap)**

## Repositories

| | |
|---|---|
| [**jig**](https://github.com/fapost-jig/jig) | The framework: skills, the `jig` tool, profiles, templates and the documentation site |
| [**jig-ui**](https://github.com/fapost-jig/jig-ui) | Optional local control center: every task, epic and spec of every connected project on one page |

## Contributing

Issues and pull requests are welcome. Jig is built with Jig, so a change follows
the same route it gives your project — start with
[CONTRIBUTING.md](https://github.com/fapost-jig/jig/blob/main/CONTRIBUTING.md).

Jig is part of [FaPost Lab](https://github.com/fapost-lab).
