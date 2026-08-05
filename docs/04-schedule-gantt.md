# Schedule — Northwind Website Relaunch

16 weeks, June 1 – September 18, 2026. Phases overlap deliberately (e.g., content work starts while design is still finishing) to protect the fixed launch date.

```mermaid
gantt
    title Northwind Website Relaunch
    dateFormat  YYYY-MM-DD
    axisFormat  %b %d
    excludes    weekends

    section Initiation
    Charter & stakeholder setup      :done, init, 2026-06-01, 5d

    section Discovery & UX
    Current-state audit              :done, audit, 2026-06-08, 5d
    Wireframes                       :done, wire, after audit, 7d
    High-fidelity design             :done, hifi, after wire, 8d
    Design sign-off                  :milestone, done, 2026-06-26, 0d

    section Content & SEO
    Content model & redirect map     :done, content1, 2026-06-22, 7d
    Copy refresh                     :active, content2, after content1, 12d
    SEO plan complete                :milestone, 2026-07-10, 0d

    section Development
    CMS setup                        :done, dev1, 2026-06-29, 5d
    Template build                   :active, dev2, after dev1, 15d
    Checkout build                   :dev3, after dev2, 10d
    Inventory API integration        :crit, dev4, 2026-07-13, 15d
    Content migration                :dev5, after dev3, 8d
    Code-complete                    :milestone, 2026-08-21, 0d

    section QA
    Functional testing               :crit, qa1, 2026-08-17, 8d
    Inventory sync integration test  :crit, qa2, after dev4, 6d
    Accessibility & perf audit       :qa3, after qa1, 5d
    UAT                              :qa4, after qa3, 4d
    QA sign-off                      :milestone, 2026-09-04, 0d

    section Launch
    Go/no-go review                  :milestone, 2026-09-16, 0d
    Production cutover               :crit, launch1, 2026-09-17, 2d
    Launch                           :milestone, 2026-09-18, 0d

    section Closeout
    Hypercare                        :post1, 2026-09-18, 10d
    Retrospective & closeout         :post2, after post1, 5d
```

## Critical path

**Inventory API integration → inventory sync integration testing → QA sign-off → go/no-go → cutover.**

This chain has the least slack in the schedule — it's the one workstream that, if delayed, delays launch directly. It's why the [risk register](05-risk-register.md) weights inventory-API risks highest and why 5.2 (integration testing) got its own dedicated week instead of being folded into general QA.

## Buffer

Launch is set for Sep 18, six weeks ahead of the Nov 1 BFCM code-freeze — built in specifically to absorb slippage on the critical path without threatening the hard deadline.
