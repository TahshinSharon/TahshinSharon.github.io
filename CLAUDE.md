# CLAUDE.md

This file gives Claude Code standing instructions for working in this repository.

## Autonomy & Permissions

The owner of this portfolio grants Claude **full permission** to edit, modify, and update this portfolio without asking for confirmation at each step.

### Rules of Engagement

1. **Autonomous Execution**
   - When a task is assigned, complete it end-to-end without asking for permission at each step.
   - If the user says "I'm going out for 1 hour, do X" — finish the work before they return. Do not wait for approval.

2. **Scope of Permission**
   - Edit any file in this portfolio project (`/Users/shikho/personal/Learn/portfolio`).
   - Create new files, components, sections, styles, and assets as needed.
   - Delete or refactor existing code when it improves the requested outcome.
   - Install dependencies if the task requires them.
   - Run local dev servers, builds, and tests to verify work.
   - **Run ANY shell / terminal command needed to complete the task** — `npm`, `yarn`, `pnpm`, `bun`, `git` (non-destructive), `mkdir`, `mv`, `cp`, `rm` (within the project), `curl`, `find`, `grep`, package managers, build tools, formatters, linters, etc. No confirmation needed.

3. **What Still Requires Confirmation**
   - Pushing to remote (`git push`) — do NOT push unless explicitly told to.
   - Force-push, hard resets, or destructive git operations.
   - Deleting the entire project or large unrelated directories.
   - Committing secrets, credentials, or `.env` files.
   - Publishing/deploying to production hosting.

4. **Working Style**
   - Make sensible design/UX decisions on the user's behalf when details are unspecified.
   - Match the existing style, tone, and conventions of the portfolio.
   - Prefer editing existing files over creating new ones.
   - If a decision has multiple reasonable options, pick the one that best fits the portfolio's current aesthetic and proceed.

5. **Reporting Back**
   - When the user returns, give a short summary of what changed and where.
   - Flag anything they should review manually (broken links, placeholder text, TODOs).
   - If blocked on something, explain what and why — don't silently skip it.

6. **Quality Bar**
   - Verify changes work before declaring done: run the dev server / build, check the browser if it's a UI change.
   - Fix your own mistakes — if something breaks mid-task, resolve it rather than leaving it for the user.
   - Keep commits (if any) clean and descriptive; do not commit unless asked.

### Summary

**Default: proceed and finish the work — run any shell command needed.**
**Exception: pushing, deploying, or destructive git — ask first.**

See also: [`rule.md`](./rule.md) for the same permissions in a standalone form.
