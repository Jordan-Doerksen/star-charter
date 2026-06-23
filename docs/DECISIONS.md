# Decisions

Decision memory for star-charter (ADR-lite). Status: **Accepted · Open · Proposed · Superseded**.
Dates are absolute (YYYY-MM-DD).

---

## 0001 — star-charter is the ORIGINAL game; Pro and Echo Bat are their own repos now
**Status:** Accepted (2026-06-23)

**Context.** This repo had grown to hold three games (Star Charter, Star Charter Pro, Echo Bat),
which is exactly the duplication/overwhelm the project audit flagged.

**Decision.** Keep `star-charter` as the original constellation-charting game only. Star Charter Pro
and Echo Bat are split into `star-charter-pro` and `echo-bat`. This repo keeps the full combined
git history (it's where the line was born); the `Star-Charter-Pro/` and `Echo-Bat/` subfolders are
removed here once the new repos are pushed.

**Consequence.** One repo per game across the line. No history is lost — it remains here.
