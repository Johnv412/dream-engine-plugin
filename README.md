# Dream Engine for Google Antigravity

Give Google Antigravity persistent, long-term memory across sessions with **Dream Engine**.

Website, privacy policy and terms: https://dreamengine.dev

Dream Engine remembers your architectural decisions, project conventions, and workflow preferences—so you don't have to repeat context every time you start a new conversation.

---

## Features

- **Automatic Context Recall** (`brain_recall`): Retrieves recent project context and preferences at the start of tasks.
- **Targeted Memory Search** (`brain_search`): Looks up past architectural decisions and lessons learned on demand.
- **Milestone Logging** (`brain_log`): Records short, plain-English summaries of key decisions and milestones.
- **Connection Check** (`brain_status`): Confirms your Dream Engine connection and active brain status.
- **Privacy-First Rules**: Built-in rules strictly prohibit logging source code, API keys, passwords, or private secrets.

---

## Installation

Marketplace listing: coming soon.

Install this plugin from GitHub using the Antigravity CLI:

```bash
agy plugin install https://github.com/Johnv412/dream-engine-plugin
```

---

## Configuration

When you enable the plugin, Antigravity will prompt you for your `DREAM_ENGINE_API_KEY`—a required key starting with `de_` that opens your brain only (self-service dashboard: coming soon).

---

## Get a key

Dream Engine is invite-only for now. To ask for a key, open an issue at https://github.com/Johnv412/dream-engine-plugin/issues (do not paste any key or password in the issue).

---

## Quick Start

Once installed and configured, try one of these prompts in Antigravity:

- *"Check my Dream Engine memory status and recall recent context."*
- *"Search Dream Engine memory for past architectural decisions and preferences."*
- *"Log today's key architectural decisions and milestones to Dream Engine."*

---

## Security & Privacy

This plugin ships with strict built-in memory rules (`rules/AGENTS.md`):

- **Never logged:** source code, file contents, API keys, passwords, tokens, or private secrets.
- **What is logged:** short, plain-English architectural decisions, milestone summaries, and preferences.

---

## Support

Self-service dashboard: coming soon. For questions or key requests, open an issue at https://github.com/Johnv412/dream-engine-plugin/issues.
