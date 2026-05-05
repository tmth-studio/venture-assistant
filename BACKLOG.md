# Backlog

Issues and improvements identified through testing.

---

## Bugs

### ~~`/find-your-venture` skill throws "Unknown skill" error~~ — FIXED
**Reported:** April 2026 (test user session)  
**Fixed:** May 2026  
**Root cause:** All skills were in `.claude/skills/` — Claude Code's Skill tool requires files to be in `.claude/commands/` to appear in the available-skills list. Skills in `.claude/skills/` are readable by Claude directly but not discoverable via the `/skill-name` invocation mechanism.  
**Fix applied:** Created `.claude/commands/` and copied all five skill files there. Skills now registered as native Claude Code slash commands.

---
