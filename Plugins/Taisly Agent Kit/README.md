# Taisly Agent Kit

> Codex plugin and MCP integration for publishing approved short-form videos through Taisly.

Publish short-form videos to TikTok, Instagram Reels, YouTube Shorts, X, and Facebook from Codex through Taisly.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Taisly Agent Kit |
| Category | Integrations / MCP / Social Media |
| Created By | Taisly |
| Type | Codex Plugin and remote MCP server |
| Best For | AI-assisted short-form video publishing |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | https://github.com/taisly/agent |
| Website | https://taisly.com |
| Codex Plugin Manifest | https://raw.githubusercontent.com/taisly/agent/HEAD/.codex-plugin/plugin.json |
| MCP Endpoint | https://app.taisly.com/mcp |

---

# Features

- Publish approved short-form videos from Codex
- Connect to TikTok, Instagram Reels, YouTube Shorts, X, and Facebook
- Use the official Taisly remote MCP server
- Includes a social media posting skill for safer agent workflows
- Supports local package usage through @taisly/agent

---

# Setup in Codex

Remote MCP setup:

```bash
codex mcp add taisly --url https://app.taisly.com/mcp
codex mcp login taisly
```

Local MCP setup:

```bash
codex mcp add taisly -- npx @taisly/agent mcp
```
