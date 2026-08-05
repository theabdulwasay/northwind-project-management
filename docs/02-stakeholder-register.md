# Stakeholder Register — Northwind Website Relaunch

## Power/interest map

```
High power  │  Marcus Webb (IT Dir.)        │  Elena Ruiz (Sponsor)
            │  → Manage closely             │  → Manage closely
            │────────────────────────────────────────────────────
Low power   │  Store Managers (x40)         │  Customer Support Lead
            │  → Keep informed              │  → Keep satisfied
            └────────────────────────────────────────────────────
              Low interest                    High interest
```

## Register

| Stakeholder | Role | Interest | Influence | Engagement strategy |
|---|---|---|---|---|
| Elena Ruiz | Sponsor, VP Marketing | Conversion, brand, launch timing | High | Weekly 1:1, decision authority on scope changes |
| Marcus Webb | IT Director | System stability, security, integration risk | High | Bi-weekly steering review, escalation path for infra risk |
| Priya Nair | Warehouse Systems Lead | Inventory API load, data integrity | Medium | Included in technical design reviews; owns API SLA |
| Dana Osei | Customer Support Lead | Ticket volume, agent tooling | Medium | Consulted on stock-accuracy requirements, notified pre-launch |
| Store Managers (40) | Store operations | Site accuracy affects in-store pickup | Low | Monthly email digest, FAQ before launch |
| UX/Design team (2) | Delivery team | Design direction, timeline | High | Daily standup, weekly design review |
| Engineering team (3) | Delivery team | Technical feasibility, scope creep | High | Daily standup, sprint planning |
| QA Engineer | Delivery team | Test coverage, launch readiness | High | Daily standup, entry/exit criteria sign-off |
| Legal/Compliance | Reviewer | Accessibility (WCAG 2.1 AA), privacy | Low | Consulted at design freeze and pre-launch review |
| Finance | Budget owner | Spend against approved budget | Medium | Monthly budget reconciliation |

## Engagement notes

- **Elena Ruiz** cares most about the mobile conversion number — every steering update leads with that metric.
- **Marcus Webb** was skeptical of the CMS migration timeline; addressed by adding a dedicated integration-testing week (see [WBS](03-scope-statement-and-wbs.md) 5.2) rather than compressing QA.
- **Store Managers** are low-influence but high blast-radius if surprised — a launch-week FAQ and support script prevents a flood of store-level questions from becoming an issue.
