# CampusPool — Professional QA & QC Reports

**Student:** Tehzeeb · University of Karachi · SQET/ST
**Application under test:** https://carpool.33.jugaar.ai (React 18 + Vite · Express + Sequelize · JWT · Caddy + PM2)
**Assessment campaign:** 8 October 2026 (v2.0 consolidated)

## Deliverables (this repository contains only these 5 files)

| File | Description |
|---|---|
| `CampusPool_QC_Report.pdf` | **Quality Control volume** (main bug report, 114 pages A4) — 84 Lewis-format defect pages (one bug per page: Title, ID, Severity, Priority, Reproducible Steps, Screenshot, Oracle, Actual, Environment, Impact), analytics charts & risk heat-map, **Section 4: Simulation-based QC (methods, tools, graphical view, result)**, master register, **appendices (Features · Tools · Techniques · Links)**, page-numbered footers |
| `CampusPool_QC_Report.docx` | Same QC volume, editable Word |
| `CampusPool_QA_Report.pdf` | **Quality Assurance volume** (20 pages) — process, standards (ISO 25010 / ISTQB / OWASP), **Section 3: Expected Types of Testing Techniques** (Functional · Exploratory · UI · Usability · Cross-browser · Responsiveness · Performance · Security), the 133-technique bundle, defect-management rules, gap-priority charts, recommendations, sign-off, page-numbered footers |
| `CampusPool_QA_Report.docx` | Same QA volume, editable Word |
| `README.md` | This summary |

## Headline numbers

- **108 findings** = 84 field-tested defects (1 Critical · 24 High · 52 Medium · 7 Low) + 24 assessed missing-feature/requirement gaps (MF-01…MF-24)
- **133 testing techniques** documented across strategy, method, functional, UI, security and non-functional families
- **52 independent references** used during testing
- **Release verdict:** NOT READY for a real-users release (launch blockers: API-094 DB wipe on boot, CR-14 seat oversell race, API-095 fake payments, API-080/081 verification bypass, API-074/UI-006 public PII, CR-01 committed secrets)
- **QC simulation (live run 7 Nov 2026):** p50 1020 ms · p90 1450 ms · max 2243 ms · 0.88 req/s; SPA healthy (200), API origin down (502) — recorded as a dated availability observation

## Report contents at a glance

- **Features List** — 9 domains, 63 features (Appendix A, in both volumes)
- **Tools used to find the bugs** — Playwright, Chrome DevTools, Python request-agents, code review, etc. (Appendix B, in both volumes)
- **Techniques used** — 133 entries, each with usage context (Appendix C, in both volumes)
- **Helpful internet links** — 52 independent references (Appendix D, in both volumes)
- Every defect follows the **Lewis Book bug format** and occupies its own page with a real evidence screenshot
- Every PDF page carries a professional footer: report name · **Page X of Y** · course tag

© 2026 Tehzeeb — University of Karachi — SQET/ST
