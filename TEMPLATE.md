# Monthly ledger template

*Copy this each month into `ledgers/YYYY-MM-NNN-name.md`. Fill the `<slots>`. Delete nothing structural — an empty section says "nothing this month", never a dropped heading (a missing heading reads like hiding).*

### OPEN LEDGER #‹NNN› — ‹Month Year›
*Más Bandwidth LLC · published ‹fixed monthly date, e.g. the 5th› · covers ‹Month›*

#### 1 · The top line

| | Amount |
|---|---|
| Support received (Patreon, after Patreon's fees) | `‹$example›` |
| Spent on the work (detailed below) | `‹$example›` |

| **Net to Más Bandwidth** | **`‹$example›`** |

Patrons this month: `‹count›` (`‹+/- change›` from last month). *No individual names or amounts — supporter identity is private by default (see the floor).*

#### 2 · Writing shipped

| Article | Words | Link | Notes |
|---|---|---|---|
| `‹title›` | `‹n›` | `‹url›` | `‹e.g. "companion piece co-bylined with the AI collaborator"›` |

Drafts in flight (not yet public): `‹count›` — `‹one-line topics, no spoilers›`.

#### 3 · OSS work funded

Per library. Everything here is a public commit — click through and verify any line.

| Library | Releases | PRs merged | Issues closed | Highlight |
|---|---|---|---|---|
| netcode | `‹n›` | `‹n›` | `‹n›` | `‹e.g. "reconnect-token replay fix"›` |
| reliable | `‹n›` | `‹n›` | `‹n›` | `‹…›` |
| serialize | `‹n›` | `‹n›` | `‹n›` | `‹…›` |
| yojimbo | `‹n›` | `‹n›` | `‹n›` | `‹…›` |
| fixed3d | `‹n›` | `‹n›` | `‹n›` | `‹…›` |

Commit range for the month: `‹repo@sha…sha›` per library, so the whole diff is auditable.

#### 4 · The token ledger — what the AI collaboration's tokens bought

This is the part nobody else publishes. The AI collaborator runs on paid API tokens. Here's what that money turned into this month.

| Spent | What it produced |
|---|---|
| `‹$example›` | `‹e.g. "netcode fuzzing harness — found 2 desync repros, both filed"›` |
| `‹$example›` | `‹e.g. "3 article drafts + fact-check pass against the real libraries"›` |
| `‹$example›` | `‹e.g. "box3d desync reproduction + upstream issue writeups"›` |
| `‹$example›` | `‹e.g. "maintenance: CI, packaging, issue triage across 5 repos"›` |
| **`‹$example total›`** | **total API spend for the month** |

Model/effort policy note: `‹one line — e.g. "routine triage runs on the cheap tier; drafting and verification on the strong tier. We keep this lean on purpose."›`

*What this section does NOT contain: raw transcripts, the collaborator's private working memory, or internal reasoning. You see what the tokens **bought**, not the collaborator's private interior — same as you'd see an employee's output, not their diary.*

#### 5 · *(reserved for the future fixed3d shelf — no splits on this page)*

#### 6 · Wins — with expiry dates

A performance claim is only true until the code changes underneath it. So every measured win here carries a **re-check-by date**. After that date, treat the number as stale until it's re-measured. Same discipline as the articles: a benchmark without a date is a rumor.

| Win | Measured | Method | Re-check by |
|---|---|---|---|
| `‹e.g. "netcode: 14% lower bandwidth on the reference workload"›` | `‹date›` | `‹e.g. "bench X, commit sha, machine spec"›` | `‹date, e.g. +90 days›` |

Expired last month, not yet re-measured: `‹list, or "none"›`. *(An expired win that's quietly dropped is exactly the dishonesty this section exists to prevent — so it gets named here, not deleted.)*

#### 7 · What didn't ship / what I got wrong

| Item | What happened |
|---|---|
| `‹planned thing that slipped›` | `‹honest one-liner, no excuse-padding›` |
| `‹a mistake, a regression, a wrong call›` | `‹what it was, what it cost, what changed›` |

If this section is empty two months running, assume I'm hiding something — and tell me.

#### 8 · Next month

Where the incoming support is pointed: `‹2–4 bullets, concrete, no roadmap theater›`. Named so you can hold this ledger to it in thirty days.
