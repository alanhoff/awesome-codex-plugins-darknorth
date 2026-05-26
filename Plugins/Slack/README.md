# Slack

> A Codex integration plugin for Slack that enables AI-assisted communication, channel summarization, workflow automation, and team collaboration directly inside OpenAI Codex.

The Slack plugin helps developers and AI coding agents interact with Slack workspaces to streamline communication, summarize discussions, automate workflows, and improve team productivity.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Slack |
| Category | Collaboration / Communication |
| Created By | Slack Technologies |
| Type | Codex Plugin |
| Best For | Team communication and workflow automation |

---

# Contributors

| Name | Contribution |
|---|---|
| Slack Technologies | Original platform and APIs |
| Your Name | Documentation and Awesome Codex Plugins integration |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | https://github.com/slackapi |
| Website | https://slack.com |
| Documentation | https://api.slack.com |

---

# Features

- Summarize Slack channels
- Draft and send messages
- Organize team conversations
- Automate Slack workflows
- AI-assisted communication
- Team productivity enhancement
- Notification and alert management

---

# Where to Use

| Use Case | Description |
|---|---|
| Engineering Teams | Coordinate development communication |
| AI Coding Agents | Summarize discussions and tasks |
| Project Management | Track updates and workflow notifications |
| DevOps Workflows | Send alerts and deployment updates |
| Team Collaboration | Improve communication efficiency |

---

# Setup in Codex

## Prerequisites

Make sure you have:
- OpenAI Codex CLI installed
- Node.js installed
- A Slack workspace
- Slack App credentials

---

# Create a Slack App

1. Open:

```txt
https://api.slack.com/apps
```

2. Click:

```txt
Create New App
```

3. Choose:
- From scratch
- Select your workspace

---

# Add Required OAuth Scopes

Inside your Slack App:

```txt
OAuth & Permissions → Scopes
```

Recommended scopes:

```txt
channels:history
channels:read
chat:write
users:read
groups:history
im:history
```

---

# Install the Slack SDK

```bash
npm install @slack/web-api
```

---

# Register Plugin in Codex

```bash
codex plugin add slack
```

---

# Alternative Manual Configuration

Add inside:

```txt
~/.codex/config.toml
```

Example configuration:

```toml
[plugins.slack]
enabled = true
bot_token = "YOUR_SLACK_BOT_TOKEN"
```

---

# Environment Variable Setup

Store credentials securely:

```bash
export SLACK_BOT_TOKEN=xoxb-your-token
```

---

# How to Use in Codex

Once installed, reference Slack directly in prompts.

## Example Prompt

```txt
Use Slack to summarize today's engineering discussions.
```

## Another Example

```txt
Draft a deployment update message using Slack.
```

The plugin can help:
- Summarize channels
- Draft responses
- Track team updates
- Organize workflows
- Send automated notifications

---

# Example Workflow

## User Prompt

```txt
Use Slack to summarize unresolved backend deployment issues.
```

## Plugin Workflow

- Reads relevant channels
- Identifies unresolved discussions
- Summarizes key issues
- Generates actionable updates
- Drafts follow-up responses

## Final Outcome

Faster communication and improved team coordination.

---

# Benefits

| Benefit | Description |
|---|---|
| Better Communication | Organizes and summarizes discussions |
| Increased Productivity | Reduces manual communication overhead |
| Faster Team Coordination | Improves workflow visibility |
| AI-Assisted Collaboration | Enables intelligent team workflows |
| Centralized Updates | Keeps teams aligned in real time |

---

# Recommended For

- Engineering teams
- DevOps workflows
- AI coding agents
- Startup teams
- Product organizations
- Remote collaboration environments

---

# Supported Ecosystems

- Slack
- Node.js
- TypeScript
- GitHub workflows
- CI/CD systems
- Team collaboration pipelines

---

# Tags

`Slack` `Communication` `Automation` `Collaboration` `Developer Productivity`

---

# Future Improvements

- AI-generated standups
- Advanced workflow automation
- Multi-workspace support
- Intelligent channel prioritization
- Meeting summarization workflows

---

# Contributing

Contributions are welcome!

Potential contributions:
- Workflow templates
- Better Slack automations
- Notification integrations
- Team collaboration examples

---

Built for the OpenAI Codex ecosystem 🚀
