# RAID Log — Northwind Website Relaunch

RAID = Risks, Assumptions, Issues, Dependencies. Reviewed weekly in the team standup; anything Medium or above gets a line in the status report.

## Risks

| ID | Risk | Probability | Impact | Score | Response | Owner | Status |
|---|---|---|---|---|---|---|---|
| R1 | Warehouse inventory API team (0.5 FTE, shared) slips their delivery | Medium | High | High | Mitigate: locked their sprint capacity in the charter; PM has weekly sync with Priya Nair | [Your Name] | Monitoring |
| R2 | Product catalog data messier than assumed, migration takes longer | Medium | Medium | Medium | Mitigate: ran a data-quality sample in week 2 to catch this early | Content lead | Closed — sample came back clean |
| R3 | Design scope grows during high-fidelity phase ("just one more screen") | High | Medium | High | Mitigate: design freeze date set and communicated at kickoff; changes after freeze go through change control | UX lead | Monitoring |
| R4 | Load testing reveals performance issues too late to fix before launch | Low | High | Medium | Mitigate: performance testing scheduled mid-QA phase, not the last day | QA | Open |
| R5 | Concurrent store POS project pulls engineering resources | Medium | Medium | Medium | Accept + monitor: flagged to IT Director, no shared engineers currently, revisit if that changes | IT Director | Monitoring |
| R6 | Accessibility audit finds late-stage issues requiring rework | Low | Medium | Low | Mitigate: accessibility considered in design review, not just tested at the end | UX lead | Monitoring |

## Assumptions

| ID | Assumption | Validation plan |
|---|---|---|
| A1 | Existing catalog data needs light transformation only, not full re-entry | Validated week 2 via data sample (see R2) |
| A2 | No warehouse system re-platform during this project | Confirmed with IT Director at kickoff |
| A3 | Store teams don't need custom training beyond an FAQ | To confirm with Store Ops by week 12 |

## Issues (realized problems, being actively managed)

| ID | Issue | Raised | Impact | Resolution | Status |
|---|---|---|---|---|---|
| I1 | Legacy CMS export tool corrupted formatting on ~30 product descriptions | Week 5 | Delayed content QA by 2 days | Manual re-export + spot check for the affected batch | Resolved |
| I2 | Staging environment inventory API returned stale data during early integration tests | Week 7 | Blocked integration testing for 3 days | Priya's team fixed staging cache config | Resolved |

## Dependencies

| ID | Dependency | On | Needed by |
|---|---|---|---|
| D1 | Inventory API staging access | Warehouse Systems team | Start of dev phase (Jun 29) |
| D2 | Brand/legal sign-off on new product photography | Marketing & Legal | Design freeze (Jun 26) |
| D3 | DNS change window | IT Infrastructure | Launch cutover (Sep 17) |
