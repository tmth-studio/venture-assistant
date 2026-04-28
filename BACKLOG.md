# Backlog

Issues and improvements identified through testing.

---

## Bugs

### `/find-your-venture` skill throws "Unknown skill" error
**Reported:** April 2026 (test user session)  
**Symptom:** When a user types "explore venture idea", the tool attempts to run `/find-your-venture` which fails with `Error: Unknown skill: find-your-venture`. The skill file exists at `.claude/skills/find-your-venture.md` — issue is a loading/discovery problem, not a missing file.  
**Impact:** Tool recovers gracefully and continues, but the skill doesn't execute.  
**Fix:** Investigate why Claude Code isn't picking up the skill file. Check skill file formatting and CLAUDE.md skill registration.

---
