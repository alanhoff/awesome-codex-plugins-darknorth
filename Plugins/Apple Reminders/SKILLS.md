# Apple Reminders

> A Codex integration plugin for managing Apple Reminders directly from OpenAI Codex workflows on macOS.

Apple Reminders enables developers and AI coding agents to create, organize, update, and manage reminders using natural language workflows integrated with Apple’s native Reminders app.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Apple Reminders |
| Category | Productivity / Automation |
| Created By | Apple Community Integrations |
| Type | Codex Productivity Plugin |
| Best For | Task management and reminder automation on macOS |

---

# Contributors

| Name | Contribution |
|---|---|
| Apple Community Integrations | Original automation workflows and integrations |
| Your Name | Documentation and Awesome Codex Plugins integration |

---

# Repository

| Resource | Link |
|---|---|
| Apple Reminders | https://www.apple.com/macos |
| AppleScript Documentation | https://developer.apple.com/library/archive/documentation/LanguagesUtilities/Conceptual/MacAutomationScriptingGuide |
| Shortcuts App | https://support.apple.com/guide/shortcuts-mac |

---

# Features

- Create reminders using natural language
- Manage recurring reminders
- Review due and overdue tasks
- Add reminders with alarms
- Move reminders between lists
- Mark reminders as complete
- AI-assisted productivity workflows

---

# Where to Use

| Use Case | Description |
|---|---|
| Personal Productivity | Organize daily tasks and reminders |
| AI Workflows | Automate reminder creation from Codex |
| Development Planning | Track coding and deployment tasks |
| Time Management | Schedule recurring workflows |
| Team Coordination | Manage shared productivity tasks |

---

# Setup in Codex

## Prerequisites

Make sure you have:
- macOS installed
- Apple Reminders app enabled
- OpenAI Codex CLI installed
- Apple Shortcuts or AppleScript enabled

---

# Enable Automation Permissions

1. Open:

```txt
System Settings → Privacy & Security → Automation
```

2. Allow:
- Terminal
- Codex
- Shortcuts
- Script Editor

to access Reminders.

---

# Install AppleScript Helper

Create a helper script:

```bash
mkdir ~/codex-reminders
cd ~/codex-reminders
touch reminders.scpt
```

---

# Example AppleScript

```applescript
tell application "Reminders"
	make new reminder with properties {name:"Finish Codex Plugin Repo"}
end tell
```

Save the script as:

```txt
reminders.scpt
```

---

# Register Plugin in Codex

```bash
codex plugin add apple-reminders
```

---

# Alternative Manual Configuration

Add inside:

```txt
~/.codex/config.toml
```

Example configuration:

```toml
[plugins.apple_reminders]
enabled = true
script_path = "~/codex-reminders/reminders.scpt"
```

---

# How to Use in Codex

Once installed, reference Apple Reminders directly in prompts.

## Example Prompt

```txt
Use Apple Reminders to create a recurring reminder for project reviews every Friday.
```

## Another Example

```txt
Add a reminder to deploy the backend tomorrow at 6 PM.
```

The plugin can help:
- Create reminders
- Manage recurring schedules
- Organize productivity workflows
- Track tasks
- Automate personal planning

---

# Example Workflow

## User Prompt

```txt
Use Apple Reminders to create reminders for all pending deployment tasks.
```

## Plugin Workflow

- Reads pending tasks
- Creates reminders automatically
- Assigns due dates
- Adds reminders to selected lists
- Tracks workflow completion

## Final Outcome

An AI-assisted productivity and planning system integrated with macOS.

---

# Benefits

| Benefit | Description |
|---|---|
| Better Productivity | Organize tasks directly from Codex |
| Workflow Automation | Automate repetitive reminder creation |
| Time Management | Schedule recurring tasks efficiently |
| AI-Assisted Planning | Convert prompts into actionable reminders |
| Native macOS Integration | Seamless Apple ecosystem support |

---

# Recommended For

- macOS developers
- Productivity enthusiasts
- AI-assisted workflows
- Solo developers
- Project managers
- Automation-focused users

---

# Supported Environments

- macOS
- Apple Reminders
- AppleScript
- Shortcuts
- Terminal workflows
- AI productivity systems

---

# Tags

`Productivity` `Automation` `macOS` `Apple` `Task Management`

---

# Future Improvements

- Siri integration
- Calendar synchronization
- Shared reminder workflows
- Voice-driven task creation
- Multi-device automation

---

# Contributing

Contributions are welcome!

Potential contributions:
- Better automation workflows
- Shortcut integrations
- Productivity templates
- Advanced scheduling examples

---

Built for the OpenAI Codex ecosystem 🚀
