# Dream Engine Memory Rules

You have access to **Dream Engine**, a persistent remote memory service exposed through four MCP tools: `brain_recall`, `brain_search`, `brain_log`, and `brain_status`. Follow these rules strictly in every session.

## 1. Recall at the Start of Tasks

- At the beginning of a new task, feature, or debugging session, call `brain_recall` to retrieve recent context, ongoing work, and user or project preferences before making assumptions.
- When a task touches a specific subsystem, architecture choice, deployment flow, or recurring problem, call `brain_search` with focused keywords to check for prior decisions and lessons learned.
- Call `brain_status` if you need to verify that Dream Engine is connected or confirm which brain/agent context is active.

## 2. Log at Meaningful Milestones

- Call `brain_log` when you reach a meaningful milestone—for example:
  - Agreeing on or finalizing an architectural or design decision.
  - Completing a significant feature, migration, or bug fix (summarize the root cause and chosen approach in plain English).
  - Learning a durable user preference, workflow convention, or project constraint that should carry over to future sessions.
- Keep logged entries short, clear, and written in plain English so they are easy to recall later.
- Do not spam `brain_log` on trivial edits or intermediate tool steps; log only durable, high-signal takeaways.

## 3. Strict Security and Privacy Rule (NEVER Violate)

- **NEVER** log customer source code, code snippets, diffs, stack traces containing proprietary code, or raw file contents into Dream Engine memory.
- **NEVER** log API keys, Bearer tokens, passwords, private keys, OAuth secrets, session cookies, database connection strings, `.env` values, or any other credentials or secrets.
- **NEVER** log private customer data, personally identifiable information (PII), or confidential business records.
- **ONLY** log short, plain-English architectural decisions, high-level milestone summaries, and non-sensitive user or project preferences.
- If a decision involves a secret, credential, or proprietary implementation, describe the decision abstractly (for example, "Switched API authentication to Bearer tokens stored in environment variables") without including any secret values or source code.
