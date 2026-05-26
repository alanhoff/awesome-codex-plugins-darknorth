# codex-profiles

> A Codex utility plugin that enables seamless switching between multiple OpenAI Codex CLI and Codex Desktop accounts using isolated `CODEX_HOME` profiles.

codex-profiles helps developers manage multiple Codex identities without copying authentication files manually, making multi-account workflows cleaner, safer, and easier to maintain.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | codex-profiles |
| Category | Codex CLI / Developer Tools |
| Created By | Community Contribution |
| Type | Codex Utility Plugin |
| Best For | Multi-account Codex profile management |

---

# Contributors

| Name | Contribution |
|---|---|
| Community Contribution | Original profile isolation workflow concept |
| Your Name | Documentation and Awesome Codex Plugins integration |

---

# Repository

Currently no official public repository available.

> You can contribute one by submitting a pull request.

---

# Features

- Multiple isolated Codex profiles
- CLI and Desktop account switching
- Profile-based authentication management
- Separate workspace environments
- Avoid manual auth file copying
- Cleaner multi-account workflows
- Environment isolation

---

# Where to Use

| Use Case | Description |
|---|---|
| Multiple OpenAI Accounts | Switch between personal and work accounts |
| Development Teams | Maintain isolated project environments |
| Testing Workflows | Use separate profiles for staging and production |
| AI Agent Systems | Run agents under different Codex identities |
| Advanced Codex Users | Manage multiple development environments |

---

# Setup in Codex

## Prerequisites

Make sure you have:

- OpenAI Codex CLI installed
- Codex Desktop (optional)
- Terminal access
- Multiple Codex accounts (optional)

---

# Create Profile Directories

Create isolated profile folders:

```bash
mkdir -p ~/.codex/profiles/work
mkdir -p ~/.codex/profiles/personal
mkdir -p ~/.codex/profiles/testing
```

---

# Set CODEX_HOME

Switch profile:

```bash
export CODEX_HOME=~/.codex/profiles/work
```

Example:

```bash
export CODEX_HOME=~/.codex/profiles/personal
```

---

# Login With Profile

Authenticate separately for each profile:

```bash
codex login
```

Credentials will be stored only inside the selected profile.

---

# Optional Alias Setup

Add aliases to:

```bash
~/.zshrc
```

or:

```bash
~/.bashrc
```

Example:

```bash
alias codex-work='export CODEX_HOME=~/.codex/profiles/work'

alias codex-personal='export CODEX_HOME=~/.codex/profiles/personal'

alias codex-test='export CODEX_HOME=~/.codex/profiles/testing'
```

Reload shell:

```bash
source ~/.zshrc
```

---

# How to Use in Codex

Switch profile:

```bash
codex-work
```

Run Codex:

```bash
codex
```

Switch again:

```bash
codex-personal
```

---

# Example Workflow

## Scenario

You have:

- Personal OpenAI account
- Work OpenAI account
- Testing account

## Workflow

- Switch to work profile
- Log into work account
- Build company projects
- Switch to personal profile
- Continue personal development

## Final Outcome

Clean profile isolation without copying authentication files manually.

---

# Benefits

| Benefit | Description |
|---|---|
| Cleaner Workflows | Removes manual authentication management |
| Profile Isolation | Keeps environments independent |
| Easier Account Switching | Switch accounts instantly |
| Better Security | Prevents accidental account mixing |
| Developer Productivity | Supports multi-context development |

---

# Recommended For

- OpenAI Codex power users
- Freelancers
- Developers with multiple accounts
- AI researchers
- Team environments
- Multi-agent systems

---

# Supported Environments

- OpenAI Codex CLI
- Codex Desktop
- macOS
- Linux
- Windows WSL
- Terminal workflows

---

# Tags

`Codex CLI` `Developer Tools` `Profiles` `Productivity` `Multi-Account`

---

# Future Improvements

- GUI profile switching
- Profile synchronization
- Automatic profile detection
- Secure profile encryption
- Team profile sharing

---

# Contributing

Contributions are welcome!

Potential contributions:

- Profile templates
- Shell integrations
- Cross-platform support
- Better workflow examples

---

Built for the OpenAI Codex ecosystem 🚀
