# Run Manifest — NV-2026-21 · Pivot Fitness

- **Run date:** 2026-07-16
- **Contract:** NV-2026-21 (Pivot Fitness · pivotgym.fit · Kaysville, UT)
- **Workspace:** northvistadigitalmarketing/nv-boost-pivot-fitness (public · demo)
- **Live site:** https://northvistadigitalmarketing.github.io/nv-boost-pivot-fitness/
- **Doc set:** nv-boost-pivot-fitness
- **Mode:** AUTO-RUN · demo client (noindex + disclaimer; personal contact + terms sanitized)

## Outcomes

| ID | Deliverable | Class | Tier | Decision | Result | Commit / Ref |
|----|-------------|-------|------|----------|--------|--------------|
| P0 | Provision repo + profile + Pages | precursor | session | run | complete | 1b023211 (README) · 4dbcf483 (profile) |
| D1 | Conversion landing page (`docs/index.html`) | artifact | skill | run | published | e3aa6617 |
| D2 | Blog — beginner strength training (`docs/blog/`) | artifact | skill | run | published | 4986dc26 |
| D3 | Signed MSA → doc set | file | session | run | filed | exec CEC_auto_7642b184 |
| D4 | LP + blog .txt renditions → doc set | file | session | run | filed | CEC_auto_c334dc7b (LP) · CEC_auto_6f3a80cd (blog) |
| D5 | Google Search ads spec (`campaigns/`) | artifact | skill | run (spec) | committed — launch GATED | 623b680d |
| D6 | Paid Meta ads | ongoing_service | — | hold | GATED (spend/launch) | — |
| D7 | Dashboard / CRM / call tracking | ongoing_service | conversation | hold | ongoing (GoHighLevel) — not built this run | — |
| D8 | Page-opt strategy / AI-search (GEO) | ongoing_service | — | hold | deferred | — |

## Doc-set filings (query surface: `nv-boost-pivot-fitness`)
- `NV-2026-21-Pivot-Fitness-MSA.pdf` — signed contract — exec CEC_auto_7642b184 — filed
- `pivot-fitness-landing-page.txt` — rendition of `docs/index.html` — exec CEC_auto_c334dc7b — filed
- `pivot-fitness-blog-strength-training.txt` — rendition of `docs/blog/how-to-start-strength-training-beginner-kaysville.html` — exec CEC_auto_6f3a80cd — filed

## Gates honored
- No real ad spend; no live campaign launched. Google Search campaign is a committed spec pending client approval + funded account (MSA §8: spend billed directly to client).
- Demo safety: repo public for Pages; every page `noindex` + demo disclaimer; commercial terms + personal contact sanitized from the public profile (live in the signed MSA in the doc set).

## Notes / open items
- MSA client signature block is blank (unsigned) — treated as a demo run.
- Orchestrator skill references template `North-Vista-Marketing`; the live template is `North_Vista_Digital_Marketing`. Provisioning used the correct live name — skill string should be corrected.
- Delivery-log rows consolidated in one profile update this run (rather than per-commit) for demo efficiency.
- Recurring services (dashboard/CRM/call-tracking, Meta ads, GEO) to be provisioned as Krista conversations in a follow-up.

---
Generated 2026-07-16 · North Vista Marketing Boost orchestrator