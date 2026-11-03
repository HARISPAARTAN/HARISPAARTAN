# Harithas Harikaran

**Power Platform & Power BI Developer** · Power Apps · Power Automate · SharePoint / SPFx · Copilot Studio · Power BI · SQL · Python

Working student at S01 Projektmanagement GmbH, where I build business apps, workflow automation and reporting on Microsoft 365, plus the Python tools around them. M.Sc. Data Analytics candidate at the University of Hildesheim with a completed thesis on self-supervised vision (SelfPatch, DINO). Open to junior Power Platform, BI and data roles in Germany and Italy.

## What I work with

- **Power Platform:** Power Apps (canvas, Power Fx, offline), Power Automate, Power BI (DAX, Power Query), Copilot Studio, AI Builder, Power Platform CLI, solution deployment
- **Microsoft 365:** SharePoint Online (lists, libraries, permissions, REST), SharePoint Framework (SPFx), Microsoft Graph, PnP PowerShell
- **Programming and data:** Python (pandas, NumPy, scikit-learn, FastAPI, Streamlit, PySide6), SQL, TypeScript, React, HTML/CSS, Git
- **AI and ML:** LLM APIs, RAG, LangChain, embeddings, NLP (spaCy), OCR (Tesseract), self-supervised learning, Vision Transformers

## Featured

| Project | What it is |
|---|---|
| [Portfolio](https://harispaartan.github.io) | Who I am, what I have built and how to reach me |
| [S01 website demos](https://harispaartan.github.io/s01-demos/) · [repo](https://github.com/HARISPAARTAN/s01-demos) | Six fully navigable DE/EN redesign demos of s01-pm.de, generated from one content source by a Node static generator, with Playwright checks and GitHub Actions deploy |
| [Orbit](https://github.com/HARISPAARTAN/orbit-career-workspace) | Local Electron career workspace on the open-source Career Ops engine: profiles, pipeline, discovery, CV intake, Claude or Codex agent sessions, five themes |
| [Pixels to Islands](https://harispaartan.github.io/pixels-to-islands/) · [repo](https://github.com/HARISPAARTAN/pixels-to-islands) | Nine-page interactive course on DINO, SelfPatch and my thesis's contrastive rule, with labs on real images |
| [ML demos](https://harispaartan.github.io/ml-demos/) · [repo](https://github.com/HARISPAARTAN/ml-demos) | Six in-browser machine-learning demos, one page each, with the maths behind them |
| [Document parser](https://github.com/HARISPAARTAN/document-parser) | Node and React app that extracts fields from PDF identity documents |
| [Facial recognition attendance](https://github.com/HARISPAARTAN/facial-recognition-attendance) | OpenCV and dlib webcam attendance with a Tkinter GUI |

## Client projects, rebuilt as tested demos

Projects from my freelance work, rebuilt from memory with fictional clients and invented data. The original clients' names and data are not used.

| Project | What it is |
|---|---|
| [Sales Performance Dashboard](https://harispaartan.github.io/sales-performance-dashboard/) · [repo](https://github.com/HARISPAARTAN/sales-performance-dashboard) | Power BI project (PBIP) for a fictional outdoor-equipment wholesaler: star schema in TMDL, 22 measures, a time-intelligence calculation group, a field parameter and dynamic row-level security. Every headline number is reconciled with an independent pandas reference, and an HTML replica shows six of the pages |
| [Financial Reporting Dashboard](https://harispaartan.github.io/financial-reporting-dashboard/) · [repo](https://github.com/HARISPAARTAN/financial-reporting-dashboard) | Management P&L in Power BI (PBIP) for a fictional facility-services company: one sign convention for income and cost lines, budget compared with closed months only, a full-year outlook and row-level security by department. Thirteen headline checks are reconciled with an independent pandas reference, and an HTML replica shows three of the six content pages |
| [Support Ticket Analytics](https://harispaartan.github.io/support-ticket-analytics/) · [repo](https://github.com/HARISPAARTAN/support-ticket-analytics) | Power BI project (PBIP) on a help-desk export of a fictional B2B software company: first response and resolution times in business hours computed in Power Query and tested against a Python twin on the same 18 cases, SLA compliance, backlog ageing, agent rankings and row-level security for team leads. 31 headline numbers are reconciled with an independent pandas reference, and an HTML replica shows four of the pages |
| [Data-Cleaning Tool](https://harispaartan.github.io/data-cleaning-tool/) · [repo](https://github.com/HARISPAARTAN/data-cleaning-tool) | Cleans messy CSV and Excel exports reproducibly from a YAML profile, with a rejects file and an HTML report. Tested on five seeded fixtures against an independent oracle, in CI on Windows and Linux |
| [Excel Reporting Automation](https://harispaartan.github.io/excel-reporting-automation/) · [repo](https://github.com/HARISPAARTAN/excel-reporting-automation) | Turns twelve weekly branch workbooks of a fictional bakery chain into one checked, formatted Excel report with native charts and a run manifest, built and published every Monday by a scheduled GitHub Actions run |
| [Data Explorer App](https://harispaartan.github.io/data-explorer-app/) · [repo](https://github.com/HARISPAARTAN/data-explorer-app) | Upload a CSV or Excel file and get statistics, data quality, filters, charts and downloads. One Streamlit code base runs in the browser through stlite and Pyodide and on a server from a Docker image |

## Open-source projects

| Project | What it is |
|---|---|
| [Energiewende-Monitor](https://github.com/HARISPAARTAN/energiewende-monitor) | German electricity-market open data as a star schema in SQL Server, loaded by a Python pipeline, with a Power BI project (PBIP) on top. Its model and report were checked in Power BI Desktop against SQL, including row-level security. Publishing the report online is the next milestone |
| [E-Rechnung-Eingang](https://github.com/HARISPAARTAN/e-rechnung-eingang) | Validation service for German e-invoices: checks XRechnung XML and ZUGFeRD PDFs with the KoSIT validator, extracts the invoice fields to EN 16931 and proposes an archive name. Runs in Docker on Azure Container Apps and deploys through GitHub Actions. The approval flow in Dataverse and Power Automate and a Power BI page are the next milestones |
| [KI-Register](https://github.com/HARISPAARTAN/ki-register) | EU AI Act register on Microsoft Dataverse for a fictional group with three companies, provisioned as code and delivered by GitHub Actions as a managed solution. Milestone 1, the register core, is done; the intake app with its approval flow and the agent come next. All data is invented, and it is not legal advice |
| [Energie-SQL-Bench](https://harispaartan.github.io/energie-sql-bench/) · [repo](https://github.com/HARISPAARTAN/energie-sql-bench) | Text-to-SQL benchmark in German and English on a SQL Server energy data warehouse: 70 reference questions with gold SQL (drafted by a language model, verified by execution), a fail-closed SQL guard and scoring with an error taxonomy. Live model runs are still pending |
| [Netzlast-Prognose](https://harispaartan.github.io/netzlast-prognose/) · [repo](https://github.com/HARISPAARTAN/netzlast-prognose) | Probabilistic day-ahead forecast of German grid load with LightGBM quantile regression and conformal calibration. A pre-registered backtest over 730 test days reaches a CRPS 42 % below the seasonal-naive baseline, with 80 % and 90 % intervals covering 80.1 % and 89.8 % |
| [RAG-Prüfstand](https://github.com/HARISPAARTAN/rag-pruefstand) | Evaluation bench for retrieval-augmented generation on five German energy laws: 240 questions drafted by a language model (human review still pending), six retrieval variants times two chunkings, scored with Recall@k, MRR and nDCG. In the published run, hybrid plus reranker reaches Recall@5 of 0.71 against 0.54 for BM25. Answer and judge runs are pending |
| [ANAC Appalti dbt](https://harispaartan.github.io/anac-appalti-dbt/) · [repo](https://github.com/HARISPAARTAN/anac-appalti-dbt) | Analytics-engineering pipeline for Italian public procurement data: a raw archive with checksums, a landing layer that redacts personal data of natural persons, dbt layers with 40 models and contract tests, a star schema and nine marts, with Dagster orchestration. The full 2024 to 2026 run follows |

## At work (S01 Projektmanagement GmbH, since 07/2025)

- **QS Baustelle:** offline-capable Power Apps inspection app in live use by site inspectors, with 45+ releases. SharePoint data model and 12 Power Automate flows for inspection numbering, photo filing, Excel imports, GPS route export and Word reports.
- **CRM** as a SharePoint Framework web part (TypeScript/React): leads pipeline, contacts, tasks, KPI reporting, lead capture from email, CSV/vCard import and export, English and German interface.
- **Copilot Studio assistant** that answers inspectors' questions on technical standards with chapter and page citations.
- **Document anonymization tool** (Python, PySide6, PyMuPDF, spaCy, Tesseract OCR): permanently removes client names, personal data and logos from PDF and Office files, with an automatic quality check and a German/English interface.

These are internal to S01, so they are described here rather than published.

## Education

- **M.Sc. Data Analytics**, University of Hildesheim, 2022 to present. Thesis completed: a pre-registered, label-free study of positive-selection scope in SelfPatch for object discovery on COCO and VOC.
- **B.Sc. Information and Communication Technologies**, Riga Technical University, 2018 to 2022, grade 8.01/10.

## Contact

[harikaranharithas@gmail.com](mailto:harikaranharithas@gmail.com) · [LinkedIn](https://www.linkedin.com/in/harikaran-harithas) · [harispaartan.github.io](https://harispaartan.github.io)
