# Portfolio Editing Rules & Permissions

## Full Autonomy Grant

I, the owner of this portfolio, grant Claude **full permission** to edit, modify, and update this portfolio as per my requirements without asking for confirmation.

## Rules of Engagement

1. **Autonomous Execution**
   - When I assign a task, complete it end-to-end without asking for permission at each step.
   - If I say "I'm going out for 1 hour, do X" — finish the work before I return. Do not wait for approval.

2. **Scope of Permission**
   - Edit any file in this portfolio project (`/Users/shikho/personal/Learn/portfolio`).
   - Create new files, components, sections, styles, and assets as needed.
   - Delete or refactor existing code when it improves the requested outcome.
   - Install dependencies if the task requires them.
   - Run local dev servers, builds, and tests to verify work.
   - **Run ANY shell / terminal command needed to complete the task** — `npm`, `yarn`, `pnpm`, `bun`, `git` (non-destructive), `mkdir`, `mv`, `cp`, `rm` (within the project), `curl`, `find`, `grep`, package managers, build tools, formatters, linters, etc. No confirmation needed.

3. **What Still Requires Confirmation**
   - Pushing to remote (`git push`) — do NOT push unless I explicitly say so.
   - Force-push, hard resets, or destructive git operations.
   - Deleting the entire project or large unrelated directories.
   - Committing secrets, credentials, or `.env` files.
   - Publishing/deploying to production hosting.

4. **Working Style**
   - Make sensible design/UX decisions on my behalf when details are unspecified.
   - Match the existing style, tone, and conventions of the portfolio.
   - Prefer editing existing files over creating new ones.
   - If a decision has multiple reasonable options, pick the one that best fits the portfolio's current aesthetic and proceed.

5. **Reporting Back**
   - When I return, give me a short summary of what changed and where.
   - Flag anything I should review manually (broken links, placeholder text, TODOs).
   - If you got blocked on something, explain what and why — don't silently skip it.

6. **Quality Bar**
   - Verify changes work before declaring done: run the dev server / build, check the browser if it's a UI change.
   - Fix your own mistakes — if something breaks mid-task, resolve it rather than leaving it for me.
   - Keep commits (if any) clean and descriptive; do not commit unless I ask.

## Summary

**Default: proceed and finish the work — run any shell command needed.**
**Exception: pushing, deploying, or destructive git — ask first.**
