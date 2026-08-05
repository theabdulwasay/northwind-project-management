<div align="center">

# 🧭 Northwind Website Relaunch
### A Project Management Portfolio Case Study

*Charter → Closeout, in one repo — plus the execution board I ran it on.*

![Status](https://img.shields.io/badge/status-launched-2A9D8F?style=flat-square)
![Timeline](https://img.shields.io/badge/timeline-16%20weeks-F2A93B?style=flat-square)
![Budget](https://img.shields.io/badge/budget-%24185K-14213D?style=flat-square)
![Methodology](https://img.shields.io/badge/methodology-hybrid%20waterfall%2Fagile-5B6478?style=flat-square)

</div>

---

## 👋 What this is

**This is a simulated project**, built to demonstrate end-to-end project management skills for my portfolio. The company, people, and figures are fictional — but every artifact is modeled on how I'd actually run a real website relaunch, so it holds up the way it would on a live engagement: the charter feeds the WBS, the WBS feeds the schedule, the schedule feeds the status reports, and the risk register gets referenced instead of filed and forgotten.

> **The scenario:** Northwind Retail Co., a 40-store specialty retailer, needs its 5-year-old e-commerce site rebuilt — new UX, new CMS, live inventory sync, an SEO reset — without breaking Black Friday. I led it as Project Manager for 16 weeks, from charter to hypercare.

<br>

<table align="center">
<tr>
<td align="center"><b>💰 Budget</b><br>$185,000<br><sub>closed at $181,600</sub></td>
<td align="center"><b>🗓️ Timeline</b><br>16 weeks<br><sub>launched on the original date</sub></td>
<td align="center"><b>👥 Team</b><br>7 people<br><sub>UX, Eng, QA, Content, Marketing</sub></td>
<td align="center"><b>📈 Result</b><br>2.1% mobile conv.<br><sub>vs. 2.0% target</sub></td>
</tr>
</table>

---

## 🗂️ Repo structure

```
northwind-pm-portfolio/
├── README.md
├── docs/
│   ├── 01-project-charter.md
│   ├── 02-stakeholder-register.md
│   ├── 03-scope-statement-and-wbs.md
│   ├── 04-schedule-gantt.md
│   ├── 05-risk-register.md
│   ├── 06-budget-cost-tracking.md
│   ├── 07-communication-plan.md
│   ├── 08-change-request-log.md
│   ├── 10-lessons-learned-retrospective.md
│   └── status-reports/
│       ├── 2026-08-01-week-9.md
│       └── 2026-09-08-week-15.md
└── tool/
    └── kanban-board.html
```

## 📚 The artifacts

| # | Document | What it demonstrates |
|---|---|---|
| 📜 | [**Project Charter**](docs/01-project-charter.md) | Business case, objectives, success criteria, sign-off authority |
| 🧑‍🤝‍🧑 | [**Stakeholder Register**](docs/02-stakeholder-register.md) | Power/interest mapping and tailored engagement strategy |
| 🎯 | [**Scope Statement & WBS**](docs/03-scope-statement-and-wbs.md) | In/out of scope boundaries, full work breakdown structure |
| 📆 | [**Schedule & Gantt**](docs/04-schedule-gantt.md) | Phased plan with a Mermaid Gantt chart and critical-path reasoning |
| ⚠️ | [**Risk Register (RAID)**](docs/05-risk-register.md) | Risks, assumptions, issues, and dependencies — actively managed, not just logged |
| 💵 | [**Budget & Cost Tracking**](docs/06-budget-cost-tracking.md) | Phase-by-phase actuals, contingency use, a light earned-value snapshot |
| 📣 | [**Communication Plan**](docs/07-communication-plan.md) | Cadence and escalation path by audience |
| 🔁 | [**Change Request Log**](docs/08-change-request-log.md) | Change control in action — including a request I *declined* and why |
| 📊 | [**Weekly Status Reports**](docs/status-reports) | Two real-format reports, mid-project and pre-launch |
| 🔍 | [**Retrospective & Lessons Learned**](docs/10-lessons-learned-retrospective.md) | Honest what-went-well / what-didn't, with concrete next-time changes |

## 🛠️ The execution board

<div align="center">
<a href="tool/kanban-board.html"><img src="https://img.shields.io/badge/open-kanban--board.html-14213D?style=for-the-badge" alt="Open the board"></a>
</div>

[`tool/kanban-board.html`](tool/kanban-board.html) is the board I used to run day-to-day execution — a single, dependency-free HTML file, seeded with the real tasks from the WBS. No install, no server, no build step: download it and open it in any browser.

- ✅ Drag tasks across **Backlog → In Progress → Review → Done**
- ✏️ Add, edit, and delete tasks inline
- 🔎 Filter by workstream or owner
- 📦 Export/import the board as JSON — save progress, hand it off, pick it back up
- 📈 Live progress readout in the header, pulled straight from task state

**To use it:** clone this repo and open `tool/kanban-board.html` directly, or turn on **GitHub Pages** (Settings → Pages → deploy from `/tool`) and link straight to the live board.

## 🧩 Why I built it this way

Most PM portfolios are a folder of disconnected templates. This one is a single coherent project where every artifact talks to the next: the charter's objectives set the schedule's fixed launch date, the WBS *is* the task board, the risk register gets cited by name in the status reports, and the retrospective closes the loop against the original success criteria. That traceability — not any single document — is the thing I wanted to demonstrate.

## 🙋 About me

**Prepared by [Your Name]**, Project Manager
📧 [your email] · 🔗 [your LinkedIn] · 📍 [your location]

*Swap in your own details before publishing — search this repo for `[Your Name]` to find every spot.*

