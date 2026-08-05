# Change Request Log — Northwind Website Relaunch

Any change to scope, schedule, or budget beyond the PM's $2,000 threshold goes through this log before work starts.

## CR-001

- **Raised:** Week 4, by UX Lead
- **Request:** Add a size-guide overlay component to the product page template (not in original wireframes), based on usability testing showing customers bouncing to search "size guide" externally.
- **Impact analysis:** +3 days design, +2 days dev, no schedule impact (absorbed in existing design buffer), no budget impact (existing team capacity).
- **Decision:** Approved by PM under delegated authority (no budget/schedule impact).
- **Status:** Implemented, closed Week 5.

## CR-002

- **Raised:** Week 6, by Sponsor (Elena Ruiz)
- **Request:** Add a "buy online, pick up in store" (BOPIS) indicator on product and cart pages — a marketing priority that emerged after a competitor launched the same feature.
- **Impact analysis:** +$4,200 (design + dev + QA for a new component and inventory-check logic), +0 days if absorbed into the existing inventory API integration work (R1/D1), since it reuses the same data feed.
- **Decision:** Approved by Sponsor, funded from contingency reserve. Logged as the reason contingency dropped to $15,600 (see [budget](06-budget-cost-tracking.md)).
- **Status:** In development, on track for code-complete.

## CR-003

- **Raised:** Week 8, by Customer Support Lead
- **Request:** Localization for French-Canadian customers (out of original scope).
- **Impact analysis:** Estimated +$35,000 and +4 weeks — would push launch past the Nov 1 BFCM freeze.
- **Decision:** Declined for this phase. Logged as a Phase 2 candidate per the [charter's](01-project-charter.md) out-of-scope list.
- **Status:** Closed — deferred, not rejected outright.

## What this shows

CR-003 is the important one: declining a stakeholder request isn't a failure of the change process, it's the process working. The impact analysis made the tradeoff visible, and the decision protected the fixed launch date instead of letting scope quietly expand.
