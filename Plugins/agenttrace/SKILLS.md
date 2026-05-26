# AgentTrace

> A local CLI/TUI observability tool for OpenAI Codex and AI coding-agent session history, enabling session replay, token analysis, cost tracking, and debugging workflows.

AgentTrace helps developers and AI coding agents inspect and understand session behavior by tracking tokens, cost, tool failures, latency, anomalies, and execution history.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | AgentTrace |
| Category | CLI Observability / Developer Tools |
| Created By | luoyuctl |
| Type | Codex CLI Utility |
| Best For | Session replay and coding-agent observability |

---

# Contributors

| Name | Contribution |
|---|---|
| luoyuctl | Original creator |
| Your Name | Documentation and Awesome Codex Plugins integration |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | https://github.com/luoyuctl/agenttrace |
| Documentation | https://github.com/luoyuctl/agenttrace/blob/master/README.md |

---

# Features

- Session replay
- Token usage tracking
- Cost monitoring
- Tool failure analysis
- Slow-run diagnostics
- Latency tracking
- Anomaly detection
- HTML and Markdown reporting
- Multi-agent session visibility
- TUI dashboard

---

# Where to Use

| Use Case | Description |
|---|---|
| Codex CLI Workflows | Review session history and behavior |
| Multi-Agent Systems | Inspect communication and execution patterns |
| Performance Analysis | Track slow sessions and bottlenecks |
| Cost Optimization | Review token usage and spending |
| Debugging Workflows | Understand tool failures and retry loops |

---

# Setup in Codex

## Prerequisites

Make sure you have:

- OpenAI Codex CLI installed
- Git installed
- Terminal access
- Go installed (optional)

---

# Install AgentTrace

Using Homebrew:

```bash
brew install luoyuctl/tap/agenttrace
```

Or use the installer:

```bash
curl -fsSL https://raw.githubusercontent.com/luoyuctl/agenttrace/main/install.sh | bash
```

Or build manually:

```bash
git clone https://github.com/luoyuctl/agenttrace.git

cd agenttrace

go build
```

---

# Register with Codex

Add AgentTrace as a utility workflow:

```bash
codex plugin add agenttrace
```

---

# Alternative Manual Configuration

Add to:

```txt
~/.codex/config.toml
```

Example:

```toml
[plugins.agenttrace]
enabled = true
track_tokens = true
track_costs = true
generate_reports = true
```

---

# How to Use in Codex

Launch AgentTrace:

```bash
agenttrace
```

Open session history:

```bash
agenttrace sessions
```

Analyze a session:

```bash
agenttrace inspect session-id
```

Generate report:

```bash
agenttrace report session-id
```

---

# Example Workflow

## User Prompt

```txt
Review why my Codex session consumed excessive tokens and repeatedly failed tool calls using AgentTrace.
```

## AgentTrace Workflow

- Loads session history
- Reads tool execution traces
- Identifies retry loops
- Detects failures
- Reviews token usage
- Generates diagnostic report

## Final Outcome

Clear visibility into agent behavior and workflow performance.

---

# Benefits

| Benefit | Description |
|---|---|
| Better Debugging | Understand failures and retries |
| Cost Visibility | Track AI usage and spending |
| Faster Diagnostics | Find bottlenecks quickly |
| Session Replay | Review agent execution history |
| Performance Insights | Optimize workflows and agent behavior |

---

# Recommended For

- Codex CLI users
- AI engineers
- Agent developers
- Multi-agent systems
- Power users
- Observability workflows

---

# Supported Ecosystems

- OpenAI Codex CLI
- Claude Code
- Gemini CLI
- Cursor exports
- Aider
- Local coding-agent workflows

---

# Tags

`CLI` `Observability` `Debugging` `Developer Tools` `Session Analysis`

---

# Future Improvements

- Real-time monitoring
- Web dashboard
- Team analytics
- Session comparison tools
- Distributed agent tracing

---

# Contributing

Contributions are welcome!

Potential contributions:

- Dashboard enhancements
- Additional exporters
- Analytics features
- Workflow templates

---

Built for the OpenAI Codex ecosystem 🚀
