# Project Charter — Northwind Website Relaunch

| | |
|---|---|
| **Project name** | Northwind Website Relaunch (NWR) |
| **Sponsor** | Elena Ruiz, VP of Marketing |
| **Project Manager** | [Your Name] |
| **Prepared** | May 18, 2026 |
| **Status** | Approved |

## Business case

Northwind's e-commerce site was last redesigned in 2021. It converts at 1.4% against a specialty-retail benchmark of 2.3%, isn't usable on mobile (58% of traffic), and runs on a CMS that can't connect to the new warehouse inventory system — meaning "in stock" online is frequently wrong. Customer service tickets tied to stock accuracy are up 40% year over year.

The site also needs to hold through Black Friday / Cyber Monday, which sets a hard, non-negotiable deadline.

## Objectives

1. Increase mobile conversion rate from 1.4% to at least 2.0% within 60 days of launch.
2. Achieve real-time inventory accuracy (new CMS synced to the warehouse system, <5 min lag).
3. Reduce stock-accuracy support tickets by 50%.
4. Launch no later than **September 18, 2026**, six weeks ahead of Black Friday, to allow a stabilization window.
5. Hold total spend at or under **$185,000**.

## Scope summary

New responsive front end, migration to a headless CMS, live integration with the warehouse inventory API, and an SEO reset (redirects, metadata, site structure) to protect existing search rankings. Full detail in the [scope statement and WBS](03-scope-statement-and-wbs.md).

**Explicitly out of scope:** loyalty program rebuild, in-store POS integration, non-English localization. These are logged as candidates for a Phase 2 proposal.

## Success criteria

- Site launches on or before Sep 18, 2026, with zero P1 defects at go-live.
- Mobile conversion ≥ 2.0% measured over the first 60 days post-launch.
- Inventory sync lag < 5 minutes, verified in production for 2 consecutive weeks.
- Final spend ≤ $185,000 (10% contingency included).

## High-level milestones

| Milestone | Target date |
|---|---|
| Charter approved | Jun 1, 2026 |
| Discovery & UX design complete | Jun 26, 2026 |
| Content & SEO plan complete | Jul 10, 2026 |
| Development complete (code-complete) | Aug 21, 2026 |
| QA sign-off | Sep 4, 2026 |
| Production launch | Sep 18, 2026 |
| Project closeout | Sep 25, 2026 |

## Budget authority

$185,000 total, inclusive of a $17,000 (10%) contingency reserve. The Project Manager may approve variances up to $2,000 per change without sponsor sign-off; anything above requires Elena Ruiz's approval via the [change request process](08-change-request-log.md).

## Constraints and assumptions

- **Constraint:** Launch must land before Nov 1 code-freeze for BFCM; Sep 18 target gives a 6-week buffer.
- **Constraint:** Warehouse inventory API team can only dedicate 0.5 FTE to this project (shared resource).
- **Assumption:** Existing product catalog data is clean enough to migrate with light transformation, not a full re-entry.
- **Assumption:** No major re-platforming of the warehouse system will occur during this project.

## Authority and sign-off

The Project Manager is authorized to assign tasks, manage the approved budget within the thresholds above, and make day-to-day scope decisions consistent with this charter. Material scope, schedule, or budget changes go through change control.

| Role | Name | Signature | Date |
|---|---|---|---|
| Sponsor | Elena Ruiz, VP Marketing | *approved* | May 18, 2026 |
| Project Manager | [Your Name] | *approved* | May 18, 2026 |
| IT Director | Marcus Webb | *approved* | May 19, 2026 |
