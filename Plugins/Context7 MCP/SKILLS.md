# Context7 MCP

> An MCP server that provides up-to-date documentation and real-world code examples directly to AI models and coding agents.

Context7 MCP helps Codex generate more accurate, framework-aware, and context-rich code by supplying fresh documentation and implementation references during development workflows.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Context7 MCP |
| Category | MCP / Documentation / AI |
| Created By | Upstash |
| Type | MCP Server |
| Best For | Real-time documentation and framework-aware AI coding |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | [Context7 GitHub Repository](https://github.com/upstash/context7?utm_source=chatgpt.com) |
| Website | [Context7 Official Website](https://context7.com/?utm_source=chatgpt.com) |
| NPM Package | [@upstash/context7-mcp](https://www.npmjs.com/package/@upstash/context7-mcp?utm_source=chatgpt.com) |

---

# Features

- Real-time documentation access
- Version-specific code examples
- Framework-aware code generation
- Reduced hallucinations
- Better API usage accuracy
- Improved autonomous coding workflows
- AI-ready documentation retrieval

---

# Where to Use

| Use Case | Description |
|---|---|
| OpenAI Codex | Inject live documentation into coding workflows |
| AI Coding Agents | Improve implementation accuracy |
| Full Stack Development | Work with modern frameworks and APIs |
| API Integrations | Generate more reliable API implementations |
| Learning Workflows | Understand libraries using real examples |
| Autonomous Agents | Enable framework-aware code generation |

---

# Setup in Codex

## Prerequisites

Make sure you have:
- Node.js installed
- OpenAI Codex CLI installed
- npm or npx available in terminal

---

## Install Context7 MCP in Codex

Run the following command in your terminal:

```bash
codex mcp add context7 -- npx -y @upstash/context7-mcp
```

This registers Context7 as an MCP server inside Codex. :contentReference[oaicite:3]{index=3}

---

## Verify Installation

Run:

```bash
codex mcp list
```

You should see:

```txt
context7
```

listed as an active MCP server. :contentReference[oaicite:4]{index=4}

---

## Alternative Manual Configuration

You can also configure it manually inside:

```txt
~/.codex/config.toml
```

Add:

```toml
[mcp_servers.context7]
command = "npx"
args = ["-y", "@upstash/context7-mcp"]
```

:contentReference[oaicite:5]{index=5}

---

# Optional API Key Setup

For better rate limits and performance:

1. Create a free account at:
   [Context7 Dashboard](https://context7.com/?utm_source=chatgpt.com)

2. Generate an API key

3. Add the API key:

```toml
[mcp_servers.context7]
command = "npx"
args = ["-y", "@upstash/context7-mcp", "--api-key", "YOUR_API_KEY"]
```

:contentReference[oaicite:7]{index=7}

---

# How to Use in Codex

Once installed, simply mention Context7 in prompts.

## Example Prompt

```txt
Create a Next.js authentication system using the latest App Router patterns. Use Context7.
```

## Another Example

```txt
Show me the latest Supabase authentication API. Use Context7.
```

Context7 will:
- Fetch latest documentation
- Retrieve updated code examples
- Supply framework-aware references
- Help Codex generate modern implementations

:contentReference[oaicite:8]{index=8}

---

# Example Workflow

## User Prompt

```txt
Build a Next.js middleware authentication system using JWT cookies. Use Context7.
```

## Context7 MCP

- Retrieves latest Next.js middleware docs
- Fetches authentication examples
- Supplies accurate App Router patterns
- Helps Codex avoid outdated APIs

## Final Outcome

More accurate and modern framework implementations.

---

# Benefits

| Benefit | Description |
|---|---|
| Better Accuracy | Uses updated documentation and examples |
| Reduced Hallucinations | Grounds responses in real references |
| Faster Development | Eliminates manual documentation lookup |
| Framework Awareness | Improves ecosystem-specific coding |
| Better AI Outputs | Produces more reliable implementations |

---

# Supported Ecosystems

- React
- Next.js
- Node.js
- TypeScript
- Python
- APIs and SDKs
- Modern web frameworks

---

# Recommended For

- AI coding assistants
- Full-stack developers
- Autonomous coding agents
- Framework-heavy projects
- API integrations
- Rapid prototyping

---

# Tags

`MCP` `Documentation` `AI` `Developer Tools` `Code Generation`

---

# Future Improvements

- Multi-source documentation aggregation
- Better semantic retrieval
- Advanced context ranking
- IDE integrations
- Improved version-awareness

---

# Contributing

Contributions are welcome!

Potential contributions:
- Additional setup guides
- Integration examples
- Better workflow templates
- More framework-specific examples

---

Built for the OpenAI Codex ecosystem 🚀
