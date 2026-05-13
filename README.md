<p align="center">
  <img src="docs/images/icon.png" width="150" alt="SkillDock" />
</p>

<h1 align="center">SkillDock</h1>

<p align="center">
  Manage AI Skills, MCP servers, Git updates, and coding-agent sync from one macOS app.
</p>

<p align="center">
  <a href="./README.zh-CN.md">中文说明</a>
</p>

<p align="center">
  <img alt="Version" src="https://img.shields.io/badge/version-0.1.0-blue" />
  <img alt="Platform" src="https://img.shields.io/badge/platform-macOS%20now%20%7C%20Windows%20planned-lightgrey" />
  <img alt="Preview" src="https://img.shields.io/badge/source-closed%20preview-lightgrey" />
</p>

## What It Does

SkillDock is a desktop control center for AI coding tools. It keeps your local Skills and MCP configurations visible, editable, and synced across the tools you use every day.

- **Skills library** — Install, update, delete, edit, inspect, and sync local skills.
- **Git-aware workflow** — Keep Git-based skills as real repositories, detect upstream updates, local edits, pending pushes, and preview changes before pulling or pushing.
- **Marketplace install** — Browse and install skills from `skills.sh`, `skillsmp`, and other supported sources.
- **Git and local import** — Install skills from GitHub, GitLab, Gitee, compatible Git repos, or existing local folders.
- **Multi-tool sync** — Enable skills for built-in coding tools and IDEs without hand-copying files.
- **MCP management** — Browse, import, edit, enable, disable, sync, and inspect MCP server configs.
- **MCP tools discovery** — Detect exposed MCP tools and track whether each server config is usable.

## Skills

View every installed skill, filter by status, inspect source metadata, and see Git collaboration state at a glance.

<p align="center">
  <img src="docs/images/skill_list.png" alt="Skills list" width="640" />
</p>

<p align="center">
  <img src="docs/images/skill_detail.png" alt="Skill details and tool sync" width="640" />
</p>

SkillDock preserves source information and tool enablement per skill, so a team-maintained skill can stay connected to its upstream repository while still being applied selectively to Claude Code, Codex, Cursor, Gemini CLI, Windsurf, and other tools.

## MCP

Manage MCP servers in the same workspace as skills. SkillDock scans supported app config files, shows the server command and source, and lets you enable or disable server sync per tool.

<p align="center">
  <img src="docs/images/mcp_list.png" alt="SkillDock MCP list" width="640" />
</p>

<p align="center">
  <img src="docs/images/mcp_detail.png" alt="MCP server details and tools" width="640" />
</p>

## Tools

SkillDock detects supported coding tools, shows their skill and MCP config locations, and gives you one place to manage sync targets.

<p align="center">
  <img src="docs/images/tools_list.png" alt="Supported tools" width="840" />
</p>

## Install

Install skills from marketplace sources, Git repositories, or local folders. SkillDock also separates MCP marketplace discovery so MCP servers can be installed and managed through their own lifecycle.

<p align="center">
  <img src="docs/images/skill_install.png" alt="Install skills from marketplace" width="840" />
</p>

<p align="center">
  <img src="docs/images/mcp_install.png" alt="Install MCP servers" width="840" />
</p>

## Settings

Configure the app storage directory, default editor, update checks, default install behavior, and tool support status.

<p align="center">
  <img src="docs/images/settings.png" alt="SkillDock settings" width="640" />
</p>

## Supported Tools

Claude Code · Codex · Cursor · Windsurf · IntelliJ IDEA · OpenCode · Gemini · Antigravity · Continue · GitHub Copilot · Qwen Code · Trae · Trae CN · Cline · Roo Code · Kilo Code · Kiro · Goose · Junie · Augment · CodeBuddy · Droid · OpenClaw · CommandCode · Crush · Qoder · Zencoder · Hermes · iFlow

## Download

Installers will be published on the [Releases](../../releases) page.

| Platform | Status |
| --- | --- |
| macOS | Coming soon |
| Windows | Planned |

## Getting Started

1. Download and open SkillDock.
2. Install skills from a marketplace, Git repository, or local folder.
3. Enable skills and MCP servers for your coding tools.
4. Use Git-aware status to review updates, local edits, and push previews.

## Roadmap

- [ ] Public installers.
- [ ] Clearer skill states: updateable, locally modified, pending push, conflicted.
- [ ] Fuller MCP lifecycle: install, configure, discover tools, and sync across tools.
- [ ] Better Git flows: branch selection, team repository pushback, PR/MR handoff.
- [ ] Windows support after the macOS workflow is stable.

## Open Source Plan

SkillDock is currently distributed as a public desktop app preview, but the source code is not open-sourced yet.

We plan to open source the project after the core features, documentation, and release workflow become more stable. Until an official open-source license is published in this repository, the source code and application assets remain proprietary and may not be copied, modified, redistributed, or reverse engineered without permission.
