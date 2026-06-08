# data-platform-playbook

A self-contained, single-page field guide to **data platform engineering** — pipeline &
system design, ETL/ELT, AWS Glue & PySpark, Airflow/MWAA orchestration, Redshift/Snowflake,
data quality, monitoring, and production support.

Everything lives in `index.html` (inline CSS + JS; Mermaid loaded from CDN). No build step.

## View locally

Open `index.html` in any modern browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Host on GitHub Pages

1. Create a repo named `data-platform-playbook` and push these files to `main`.
2. In **Settings → Pages**, set **Source = Deploy from a branch**, **Branch = `main` / root**.
3. Your site goes live at `https://<username>.github.io/data-platform-playbook/`.

The included empty `.nojekyll` file tells GitHub Pages to serve the static files as-is
(no Jekyll processing).

## Contents

- 47 deep questions across 7 sections, each with a consistent answer anatomy
  (how to think → decision justification → full answer → code/diagram → what not to say).
- Comparison tables, callouts, and Mermaid architecture diagrams throughout.
- A cheatsheets section for a quick night-before run-through.
