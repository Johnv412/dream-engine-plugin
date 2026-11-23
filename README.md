# Dream Engine for Google Antigravity

Give Google Antigravity persistent, long-term memory across sessions with **Dream Engine**.

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

### Option 1: Install from the Antigravity Marketplace

1. Open **Antigravity** and go to the **Plugins / Marketplace** panel.
2. Search for **Dream Engine**.
3. Click **Install**.
4. When prompted, enter your Dream Engine credentials (see [Configuration](#configuration) below).

### Option 2: Install from GitHub

You can install this plugin directly using the Antigravity CLI:

```bash
agy plugin install https://github.com/Johnv412/dream-engine-plugin
```

Or add the repository URL in the Antigravity Plugins Manager under **Install from GitHub**.

---

## Configuration

After installing, Antigravity will prompt you for your Dream Engine API key:

| Setting | Required? | What to enter |
| --- | --- | --- |
| **`DREAM_ENGINE_API_KEY`** | **Required** | Paste your API key from your [Dream Engine dashboard](https://dreamagent-abf13.web.app). |

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

Visit [https://dreamagent-abf13.web.app](https://dreamagent-abf13.web.app) to manage your API keys, brains, and account settings.
