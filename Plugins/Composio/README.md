# Composio

> A powerful integration platform that connects OpenAI Codex to thousands of apps, APIs, and MCP servers for autonomous workflows and AI-assisted automation.

Composio enables developers and AI coding agents to interact with external tools and services such as GitHub, Slack, Notion, Gmail, Linear, Google Docs, and many more using natural language workflows inside OpenAI Codex.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Composio |
| Category | Integrations / MCP / Automation |
| Created By | Composio |
| Type | MCP Integration Platform |
| Best For | Connecting Codex with external tools and APIs |

---

# Contributors

| Name | Contribution |
|---|---|
| Composio | Original platform and integrations |
| Your Name | Documentation and Awesome Codex Plugins integration |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | https://github.com/ComposioHQ |
| Website | https://composio.dev |
| Documentation | https://docs.composio.dev |

---

# Features

- Connect Codex to external apps
- MCP server integrations
- AI-powered workflow automation
- Tool calling using natural language
- Multi-platform integrations
- Autonomous agent workflows
- API orchestration

---

# Supported Integrations

- GitHub
- Slack
- Gmail
- Notion
- Linear
- Google Docs
- Jira
- Discord
- Trello
- and many more

---

# Where to Use

| Use Case | Description |
|---|---|
| AI Coding Agents | Enable external tool access inside Codex |
| Workflow Automation | Automate repetitive tasks across platforms |
| Team Collaboration | Integrate communication and project management |
| DevOps Workflows | Coordinate deployments and repositories |
| Autonomous Systems | Allow AI agents to interact with real-world tools |

---

# Setup in Codex

## Prerequisites

Make sure you have:
- OpenAI Codex CLI installed
- Node.js installed
- A Composio account
- Access to desired third-party integrations

---

# Install Composio SDK

```bash
npm install composio-core
```

Or globally:

```bash
npm install -g composio-cli
```

---

# Authenticate with Composio

Login to Composio:

```bash
composio login
```

Follow the browser authentication flow.

---

# Register Composio in Codex

```bash
codex mcp add composio -- npx composio-mcp
```

---

# Alternative Manual Configuration

Add inside:

```txt
~/.codex/config.toml
```

Example configuration:

```toml
[mcp_servers.composio]
command = "npx"
args = ["composio-mcp"]
```

---

# Connect Applications

Example integrations:

```bash
composio add github
```

```bash
composio add slack
```

```bash
composio add notion
```

---

# Verify MCP Installation

Run:

```bash
codex mcp list
```

You should see:

```txt
composio
```

listed as an active MCP server.

---

# How to Use in Codex

Once installed, reference Composio directly in prompts.

## Example Prompt

```txt
Use Composio to create a GitHub issue and notify the team in Slack.
```

## Another Example

```txt
Use Composio to summarize Linear tickets and update Notion documentation.
```

The plugin can help:
- Automate workflows
- Connect external services
- Coordinate multiple tools
- Enable AI-powered operations
- Build autonomous agent systems

---

# Example Workflow

## User Prompt

```txt
Use Composio to review GitHub pull requests and send summaries to Slack.
```

## Plugin Workflow

- Connects to GitHub
- Reads pull request data
- Summarizes changes
- Sends updates to Slack
- Tracks workflow completion

## Final Outcome

A fully automated cross-platform AI workflow.

---

# Benefits

| Benefit | Description |
|---|---|
| Massive Integration Support | Connect thousands of tools and APIs |
| AI-Powered Automation | Enable autonomous workflows |
| Faster Operations | Reduce repetitive manual tasks |
| Better Collaboration | Connect communication and development tools |
| Scalable Agent Systems | Build advanced multi-tool AI agents |

---

# Recommended For

- AI agent developers
- DevOps engineers
- Startup engineering teams
- Automation enthusiasts
- Product organizations
- Enterprise workflow systems

---

# Supported Ecosystems

- OpenAI Codex
- MCP servers
- GitHub
- Slack
- Notion
- Linear
- Google Workspace
- API-driven platforms

---

# Tags

`MCP` `Automation` `Integrations` `AI Agents` `Developer Productivity`

---

# Future Improvements

- Advanced agent orchestration
- Real-time automation monitoring
- Multi-agent integrations
- Enterprise workflow templates
- Expanded MCP ecosystem support

---

# Contributing

Contributions are welcome!

Potential contributions:
- New integration examples
- Workflow templates
- Automation strategies
- MCP configuration guides

---

Built for the OpenAI Codex ecosystem 🚀
