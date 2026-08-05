# Retrospective & Lessons Learned — Northwind Website Relaunch

Held Sep 22, 2026, four days after launch, with the full delivery team.

## Outcome against success criteria

| Success criterion | Target | Result |
|---|---|---|
| Launch date | On or before Sep 18 | Launched Sep 18 |
| Inventory sync lag | < 5 min | 1.8 min average |
| Budget | ≤ $185,000 | $181,600 final |
| Mobile conversion (60-day) | ≥ 2.0% | Tracking at 27 days: 2.1% — final read due at day 60 |

## What went well

- **Setting the design freeze date at kickoff, not mid-project**, gave the team a real deadline to design against instead of an open-ended "when it's ready." It's the reason CR-001 got absorbed cleanly instead of becoming a schedule fight.
- **Dedicating a full week to inventory integration testing (5.2)** instead of folding it into general QA. This was the highest-risk item on the critical path, and it paid off — sync lag came in well under target with no last-week surprises.
- **Weekly RAID review** meant nothing sat unaddressed for more than a week. Both realized issues (I1, I2) were resolved within days of being raised because they were already being watched for.

## What didn't go well

- **The Week 9 CPI dip caused more sponsor concern than it needed to.** The status report explained the cause, but "yellow" status without more context up front read as more alarming than the underlying numbers warranted. Next time: pair a status color change with a one-line "why this isn't a launch risk" note, not just the metric.
- **Content team was under-resourced relative to the copy refresh scope.** Product page copy finished later than category pages and ran close to the schedule buffer. If I ran this again, I'd size the content workstream against the actual page count in the charter phase, not estimate it alongside design.

## What I'd change next time

1. Build the content workstream's estimate from a page-count multiplier, not a phase-level guess.
2. Add a one-line "so what" to every status color change, not just the metric that triggered it.
3. Start the accessibility audit earlier — it passed cleanly, but running it only once mid-QA left less room to fix anything that hadn't.

## Team feedback (anonymized, from retro)

- "The daily standup stayed 15 minutes the whole project — that's rarer than it should be."
- "Would've liked earlier visibility into the BOPIS change (CR-002) before it landed on the sprint board."

That second point fed directly into change #2 above — CRs that add work need to reach the team as early as they reach the sponsor.
