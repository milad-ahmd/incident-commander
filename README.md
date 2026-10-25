<div align="center">

# 🚨 incident-commander

**Run a production outage from triage to mitigation, status updates and a blameless postmortem. An Agent Skill for Claude Code, Cline, Cursor, Codex and other AI coding agents.**

[![License: MIT](https://img.shields.io/github/license/milad-ahmd/incident-commander)](LICENSE)
[![Stars](https://img.shields.io/github/stars/milad-ahmd/incident-commander?style=social)](https://github.com/milad-ahmd/incident-commander)
![Category](https://img.shields.io/badge/category-DevOps-blue)
![Works with](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Cline%20%7C%20Cursor%20%7C%20Codex-8A2BE2)

[Install](#-install) · [Usage](#-usage) · [How it works](skills/incident-commander/SKILL.md) · [All skills](https://github.com/milad-ahmd/agent-skills)

</div>

> Part of **[agent-skills](https://github.com/milad-ahmd/agent-skills)**, a growing collection of practical skills for AI coding agents.

## 📦 Install

**One command (installs the whole collection):**

```bash
curl -fsSL https://raw.githubusercontent.com/milad-ahmd/agent-skills/main/install.sh | bash -s -- incident-commander
```

**Manually (Claude Code):**

```bash
git clone https://github.com/milad-ahmd/incident-commander /tmp/incident-commander
mkdir -p ~/.claude/skills && cp -r /tmp/incident-commander/skills/incident-commander ~/.claude/skills/
```

**Per project:** copy `skills/incident-commander` into `<project>/.claude/skills/`.
**Any other agent:** paste [`SKILL.md`](skills/incident-commander/SKILL.md) into your rules or system prompt.

## 💬 Usage

Just ask your agent:

```text
Production is down, help me
Write a postmortem for yesterday's outage
```

The full workflow, rules and output format are in [`SKILL.md`](skills/incident-commander/SKILL.md).

## 🧩 More skills

See the full collection: **[milad-ahmd/agent-skills](https://github.com/milad-ahmd/agent-skills)**.

## 🤝 Contributing

Issues and PRs are welcome, especially real-world before/after examples.

## 📄 License

[MIT](LICENSE) © Milad Ahmadi

<div align="center">

**If this skill saved you time, a ⭐ helps others find it.**

</div>
