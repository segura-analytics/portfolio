# Segura Analytics — Portfolio

This is the public portfolio of **Miguel Segura**. It showcases end‑to‑end analytics projects using **Power BI, Power Query (ETL), DAX, Excel, Power Automate**, and light **Python**.

> Tip: replace any placeholder text that says "TODO" as you publish each project.

## Projects
- [Operations KPI](./ops-kpi/README.md)
- [Cash Flow Control](./cashflow-control/README.md)
- [Support Analytics](./support-analytics/README.md)

## How this repo is organized
```
segura-analytics-portfolio/
  README.md
  ops-kpi/
  cashflow-control/
  support-analytics/
  assets/
```

- Each project folder includes: a `README.md` (case study), a `pbix/` or `pbit/` file, a `data/` folder with synthetic samples, and `docs/` (screenshots, model diagram).
- **PBIX size note:** If a `.pbix` is >100MB, use `.pbit` (template) or Git LFS (already configured via `.gitattributes`). See **PBIX / LFS** below.

## PBIX / LFS
This repo tracks `*.pbix` and `*.pbit` via Git LFS to avoid hitting GitHub's 100MB limit.  
Install LFS (one time):

```bash
git lfs install
```

If you prefer not to use LFS, upload `.pbit` templates instead and host `.pbix` on OneDrive/Google Drive, then link it in each project README.

## License
- Code: MIT (see [LICENSE](./LICENSE))
- Media/screenshots: CC BY 4.0 (optional; adjust if needed)

_Maintained by Miguel Segura — updated 2025-10-06._
