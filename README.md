# FANT — Fabric & Analytics Navigator Toolkit

End-to-end pre-sales toolkit for Microsoft Fabric, built as a single-file Vue 3 app
(Tailwind via CDN, no build step).

**Live:** https://fant.developedbytoo.me/

## Features

| Tab | Module |
| --- | --- |
| 1 | Discovery & Arsitektur — multi-select data sources, automatic Gateway/Mirroring/Shortcut detection, CU spike chart, dynamic Medallion diagram |
| 2 | Fabric & PBI FinOps — PAYG vs 1-year reservation, scheduled pause, F64+ viewer break-even |
| 3 | AI & Copilot — Azure AI Foundry token/RAG costing, Copilot, Purview, Private Link |
| 4 | Master BoQ — bill of quantities and investment summary |
| 5–6 | Architecture blueprint generator, naming standard |
| 7 | Estimator & MoM — consulting man-days per role, rate card (IDR), phase timeline |
| 8–13 | Code vault, Azure price explorer, infra calculator, data & AI services, TCO, Well-Architected |
| 14 | Client Delivery Kit |
| 15 | SOW & Proposal export (Markdown preview, copy/download) |

## Run locally

Open `index.html` directly, or serve it:

```bash
python3 -m http.server 8080
```

## Deploy

The app is served as-is by nginx:

```bash
sudo cp index.html /var/www/html/fant/index.html
```
