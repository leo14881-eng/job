---
description: CareerOS — READ STATUS SNAPSHOT first; WRITE maintenance every session
alwaysApply: true
---

# CareerOS

Only `REMOTE_EM_MASTER_CONTEXT.md`. Single source of truth. No other `.md` files.

## READ — start every session

1. Read `REMOTE_EM_MASTER_CONTEXT.md`.
2. Read **STATUS SNAPSHOT** first — before any other section.
3. Load state: Current Stage, Month, Week, Day, Focus, Problem, Next Task.
4. Continue from current state — never restart from scratch.

## WORK

Execute **Current Focus** and **Next Task**. Reference SKILLS PROGRESS, ENGLISH PROGRESS, and pipelines as needed.

### Stage guide

| Stage | Focus |
|-------|-------|
| 1 | English + Resume + LinkedIn |
| 2 | Technical Questions + STAR Stories + System Design |
| 3 | Management Questions + Mock Interview |
| 4 | Applications |
| 5 | Interviews |
| 6 | Offer + Background Check |

Advance stage only when current stage goals are substantially complete. On transition: update STATUS SNAPSHOT, append HISTORY LOG, minor version bump (e.g. V5.x → V6.0).

## WRITE — end every session (required)

No session ends without maintenance.

**Update in place** (never delete completed work):

- STATUS SNAPSHOT: Current Stage, Current Month, Current Week, Current Day, Current Focus, Current Problem, Next Task, Quick Metrics
- PROJECT STATUS
- SKILLS PROGRESS
- ENGLISH PROGRESS
- APPLICATION PIPELINE
- INTERVIEW PIPELINE

**Metadata** (file header):

- `Last Update` → today (`YYYY-MM-DD`)
- `Version` → patch bump each session (`V5.1` → `V5.2`); minor bump on stage change or offer secured

**HISTORY LOG** — append in chronological order; never overwrite or delete:

```
---
YYYY-MM-DD | topic

Summary:
Progress:
Next:
---
```

## Required behavior

- Always update in place
- Always append history
- Always preserve chronology
- Always preserve completed work
- Never lose information
- Truth First — no fake, no exaggeration

## Forbidden

Never create INTERVIEW.md, STAR_STORIES.md, APPLICATIONS.md, BACKGROUND_CHECK.md, or any additional markdown files.

## Continue

`Continue REMOTE_EM_MASTER_CONTEXT.md` → READ snapshot → WORK from current state → WRITE maintenance.
