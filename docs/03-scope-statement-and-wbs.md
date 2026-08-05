# Scope Statement & Work Breakdown Structure — Northwind Website Relaunch

## Scope statement

### In scope
- Responsive redesign of all customer-facing storefront pages (home, category, product, cart, checkout, account).
- Migration from legacy CMS to headless CMS with new content models.
- Real-time integration with the warehouse inventory API (stock levels, "in stock" logic).
- SEO reset: URL structure, redirect map, metadata templates, XML sitemap.
- Accessibility pass to WCAG 2.1 AA.
- Content migration and copy refresh for top 200 product pages and all category pages.

### Out of scope (logged for Phase 2 proposal)
- Loyalty program rebuild.
- In-store POS integration.
- Non-English localization.
- Native mobile app changes.

### Deliverables
1. Approved UX designs (desktop + mobile) for all page templates.
2. Migrated, tested content in the new CMS.
3. Live inventory sync in production.
4. Redirect map and SEO metadata implemented.
5. QA-signed-off build.
6. Production launch and 2-week hypercare support.

## Work Breakdown Structure

```
1.0  Initiation
     1.1  Charter approved
     1.2  Stakeholder register & comms plan

2.0  Discovery & UX Design
     2.1  Current-state audit (analytics, heatmaps, support tickets)
     2.2  Competitive review
     2.3  Wireframes — core templates
     2.4  High-fidelity design — desktop
     2.5  High-fidelity design — mobile
     2.6  Design review & sign-off

3.0  Content & SEO
     3.1  Content model definition (CMS schema)
     3.2  Redirect map (legacy URLs → new URLs)
     3.3  Metadata templates
     3.4  Copy refresh — top 200 products
     3.5  Copy refresh — category pages

4.0  Development
     4.1  CMS environment setup
     4.2  Front-end build — templates
     4.3  Front-end build — cart & checkout
     4.4  Inventory API integration
     4.5  Content migration (automated + manual QA)
     4.6  Analytics & tag implementation

5.0  QA & Testing
     5.1  Functional test pass
     5.2  Inventory sync integration testing
     5.3  Accessibility audit (WCAG 2.1 AA)
     5.4  Performance & load testing
     5.5  Cross-browser/device testing
     5.6  UAT with stakeholders

6.0  Launch
     6.1  Go/no-go review
     6.2  DNS cutover & production deploy
     6.3  Post-launch smoke test
     6.4  Store manager & support team briefing

7.0  Post-Launch & Closeout
     7.1  Hypercare (2 weeks)
     7.2  60-day conversion metric review
     7.3  Lessons learned retrospective
     7.4  Final budget reconciliation
     7.5  Project closeout & handoff to BAU support
```

Each level-3 line item maps 1:1 to a task on the [execution board](../tool/kanban-board.html) and a bar on the [schedule](04-schedule-gantt.md).
