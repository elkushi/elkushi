<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg">
  <img alt="Moustafa Elkoushy. I build AI workflows that check their own work." src="./assets/header-light.svg">
</picture>

Most of what I build runs on Claude Code. An agent reads a written procedure,
calls small Python tools in order, and produces a finished deliverable: a
report, a newsletter, a video.

The part I care about most is what happens when the model gets something wrong.

## What happens to a bad claim

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/pipeline-dark.svg">
  <img alt="Research agents feed a JSON schema, then a validator. Claims with no source or a dead link are blocked. Only a clean report becomes a PDF." src="./assets/pipeline-light.svg">
</picture>

My competitor-analysis workflow will not render a report if any claim has no
source, any link is dead, placeholder text is left in, or a forbidden name
appears. Its first real run covered 9 companies, with about 190 sources and
more than 400 cited claims.

## Projects

| | |
|---|---|
| [**claude-ai-workflows**](https://github.com/elkushi/claude-ai-workflows) | Agentic workflows built with Claude Code. Parallel research agents, a JSON Schema contract between steps, a validator as the gate, branded PDF output. |
| [**system-audit**](https://github.com/elkushi/system-audit) | Bash tool that audits a Linux server: SUID files, open ports, SSH config, cron jobs, sensitive file permissions, failed logins. Writes a timestamped report. |

## Background

- **Day job:** B2B messaging (SMS, WhatsApp, Viber). Website development,
  technical specs and documentation, and talking to client engineers and
  partners at industry events.
- **Before that:** Arabic AI quality at Yandex, reviewing and correcting
  answers from the Alice voice assistant.
- **Education:** MSc Software Engineering, BSc Avionics Engineering, Moscow
  Aviation Institute.
- **Languages:** Arabic (native), English and Russian (C1).

**Tools:** Python · Claude Code · JSON Schema · Django · PostgreSQL · REST APIs · Linux · Bash · Git

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/elkushi/elkushi/output/snake-dark.svg">
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/elkushi/elkushi/output/snake.svg">
</picture>

