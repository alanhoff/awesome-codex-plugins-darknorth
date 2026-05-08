# Linear Plugin

> A Codex integration plugin for managing Linear issues, development workflows, and project coordination directly inside OpenAI Codex.

The Linear Plugin helps developers and AI coding agents streamline software development workflows by integrating task management, ticket handling, and implementation coordination with Linear.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Linear Plugin |
| Category | Collaboration / Project Management |
| Created By | Linear |
| Type | Codex Plugin |
| Best For | Software project management and workflow automation |

---

# Contributors

| Name | Contribution |
|---|---|
| Linear | Original platform and integrations |
| Your Name | Documentation and Awesome Codex Plugins integration |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | https://github.com/linear |
| Website | https://linear.app |
| Documentation | https://developers.linear.app |

---

# Features

- Read and manage Linear tickets
- Generate implementations from issues
- Update project tasks
- Create PR-linked workflows
- Automate development coordination
- AI-assisted task management
- Sprint and issue tracking

---

# Where to Use

| Use Case | Description |
|---|---|
| Software Development | Manage engineering workflows directly in Codex |
| Agile Teams | Coordinate sprint and issue tracking |
| AI Coding Agents | Automate issue handling and implementation |
| Product Engineering | Connect planning with execution |
| DevOps Workflows | Track tasks and deployment coordination |

---

# Setup in Codex

## Prerequisites

Make sure you have:
- OpenAI Codex CLI installed
- Node.js installed
- A Linear account
- Linear API access token

---

## Create a Linear API Key

1. Open:

```txt
https://linear.app/settings/api
```

2. Generate a personal API key

3. Copy the API token securely

---

# Install Linear SDK

```bash
npm install @linear/sdk
```

---

# Register Plugin in Codex

```bash
codex plugin add linear
```

---

# Alternative Manual Configuration

Add inside:

```txt
~/.codex/config.toml
```

Example configuration:

```toml
[plugins.linear]
enabled = true
api_key = "YOUR_LINEAR_API_KEY"
```

---

# Environment Variable Setup

You can also store the API key securely:

```bash
export LINEAR_API_KEY=your_api_key
```

---

# How to Use in Codex

Once installed, reference Linear directly in prompts.

## Example Prompt

```txt
Use Linear to fetch my current sprint issues and generate implementation plans.
```

## Another Example

```txt
Create a PR-linked workflow for this bug fix using Linear.
```

The plugin can help:
- Read project tickets
- Summarize engineering tasks
- Generate implementation workflows
- Update issue statuses
- Coordinate development activities

---

# Example Workflow

## User Prompt

```txt
Use Linear to implement the authentication feature assigned to me.
```

## Plugin Workflow

- Fetches assigned issue
- Reads task requirements
- Generates implementation steps
- Creates development workflow
- Updates issue progress

## Final Outcome

A streamlined and AI-assisted development workflow.

---

# Benefits

| Benefit | Description |
|---|---|
| Faster Development | Automates repetitive project workflows |
| Better Coordination | Keeps tasks and code synchronized |
| Improved Productivity | Reduces manual issue management |
| AI-Assisted Planning | Converts tickets into actionable workflows |
| Better Team Collaboration | Enhances engineering coordination |

---

# Recommended For

- Software engineering teams
- Agile workflows
- AI coding agents
- Startup engineering teams
- Product development organizations
- Autonomous engineering systems

---

# Supported Ecosystems

- Linear
- GitHub
- Node.js
- TypeScript
- CI/CD workflows
- Agile engineering systems

---

# Tags

`Linear` `Project Management` `Automation` `AI Workflows` `Developer Productivity`

---

# Future Improvements

- Advanced sprint analytics
- Multi-agent task delegation
- Automated PR reviews
- Workflow orchestration
- CI/CD integrations

---

# Contributing

Contributions are welcome!

Potential contributions:
- Better workflow templates
- Example engineering pipelines
- Advanced integrations
- Multi-platform coordination

---

Built for the OpenAI Codex ecosystem 🚀
