# Hermes Tweet

> Native Hermes Agent plugin for X/Twitter research, monitoring, drafting, and explicitly approved actions through Xquik.

Hermes Tweet gives agents a focused route for X/Twitter workflows without mixing social automation into general web browsing or unrelated social tools.

---

# Overview

| Field | Details |
|---|---|
| Plugin Name | Hermes Tweet |
| Category | Integrations / Social Media / Automation |
| Created By | Xquik-dev |
| Type | Hermes Agent Plugin |
| Best For | X/Twitter reads, monitoring, drafting, follower exports, and approval-gated actions |

---

# Repository

| Resource | Link |
|---|---|
| GitHub | https://github.com/Xquik-dev/hermes-tweet |
| Installation | `hermes plugins install Xquik-dev/hermes-tweet --enable` |

---

# Features

- Search and read public X/Twitter posts, profiles, timelines, replies, and followers.
- Draft tweets or threads from campaign, support, research, or competitor context.
- Monitor mentions, replies, and social signals.
- Keep state-changing actions behind explicit runtime gates and user approval.
- Expose separate planning, read, and action tools for safer agent routing.

---

# Where to Use

| Use Case | Description |
|---|---|
| Social listening | Read public X/Twitter context and summarize concrete signals. |
| Campaign drafting | Turn launches, changelogs, or research into tweet drafts. |
| Community monitoring | Review replies or mentions before proposing responses. |
| Account actions | Publish, reply, repost, like, follow, or delete only after explicit approval. |

---

# Setup in Hermes Agent

```bash
hermes plugins install Xquik-dev/hermes-tweet --enable
hermes tools list
```

Set `XQUIK_API_KEY` in the Hermes runtime environment before authenticated reads. Set `HERMES_TWEET_ENABLE_ACTIONS=true` only when the user wants state-changing X/Twitter actions.
