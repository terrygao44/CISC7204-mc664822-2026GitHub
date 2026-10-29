# CISC7204 Assignment 02 — Data Visualization with Python (Class K)

Assignment artifacts for **CISC7204 Data Science and Data Visualization (2026/27 Semester 1)**,
submitted at the Class K support site of UMMoodle.

| | |
|---|---|
| Student | **MC664822 GAO TE** |
| Pair | **Class K - Pair 05** (partner: MC664831 WEN ZIMING) |
| Coursework item | Assignment 02 — Modules 01–05 (labs, Dash project spaces, revised pair proposal) |
| Due | 2026-10-25 23:00 |

## Repository layout

```
Module01/   Lab 01, Lab 02 — notebooks + Notebook-7 screenshots
Module02/   Lab 01, Lab 02, Lab 03 — notebooks + screenshots
Module03/   Lab 01, Lab 02 — notebooks + screenshots
Module04/   Lab 01 notebook; Lab 02/03/04 zipped Dash project spaces + screenshots
Module05/   Practice Lab 01, Final Lab 01 notebooks; Practice/Final Lab 02 zipped Dash
            project spaces + screenshots (including the two required report figures)
CISC7204-Assgn02-Pair05-RevisedProjectProposal.docx   revised pair project proposal
_POSTING_PLAN.md                                     mapping of screenshots to forum posts
```

## How to run

- **Notebooks** — open any `*.ipynb` with Jupyter Notebook / JupyterLab (tested with
  Jupyter Notebook 7, kernel `Python (spyder_work)`). All notebooks are stored with their
  executed outputs. They read their data from the course data URLs
  (`cf-courses-data.s3...`), so no local data file is required.
- **Dash project spaces** — each `*.zip` contains the application script, a `Screenshots/`
  folder and a `README.txt`:

  ```
  unzip "…Lab02 MC664822 GAO TE.zip"
  cd cisc7204_assgn02_module05practice_lab02
  python Dash_wildfire.py        # then open the local URL printed in the console
  ```

## Notes

- The five module labs are **individual** learning evidence and were completed by MC664822
  GAO TE; the revised project proposal is the **pair** deliverable of Pair 05.
- The two Module 05 project spaces are also submitted at the Module 5 Practice / Final
  submission links, together with the datasets they use
  (`Historical_Wildfires.csv`, `automobile-sales.csv`).
- Python libraries used: pandas, numpy, matplotlib, seaborn, folium, plotly, dash,
  wordcloud, pywaffle, openpyxl.
