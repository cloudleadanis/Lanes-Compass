# 🧭 Lanes Compass

Lightweight goal alignment for teams using [Lanes](https://github.com/your-repo/lanes).  
One markdown table. Weekly 10‑min async check‑in.

## Quick start

1. Copy `TEMPLATE.md` to `GOALS.md`
2. Edit the team goals and norms
3. Each person adds one row
4. Weekly: update status column (🟢/🟡/🔴) by EOD Tuesday
5. Lead reviews Wednesday → 5‑min sync for any 🔴 or 🟡

## Rules (kept in `GOALS.md`)

- **Conflict resolution**: Leader decides within 48h if personal goal blocks team goal.  
- **Escalation**: Set 🔴 + `@lead` in the cell → leader responds by next review.  
- **Mid‑cycle revision**: Any role change, market shift, blocked dependency → edit row, set status 🟡.

## Why this works

- No tabs, no spreadsheets, no meetings longer than 10 min/week.
- Every goal change is tracked via git history.
- PRs optional for formal goal changes.

## Files

- `GOALS.md` – live document for the current quarter  
- `TEMPLATE.md` – copy this each quarter  
- `.github/ISSUE_TEMPLATE/goal_conflict.md` – optional structured escalation
