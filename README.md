# House Price Prediction

## Project Overview

This four-sprint machine learning capstone will produce an end-to-end house price prediction application. The project will progress from understanding the data and establishing a baseline to selecting a final model and delivering it through a public application.

## Problem Statement

The goal of this project is to predict residential house sale prices (`price`) from property characteristics in the King County House Sales Dataset. The resulting regression solution will support consistent, data-informed price estimates and demonstrate an end-to-end machine learning workflow.

## Dataset

- **Dataset:** King County House Sales Dataset
- **Source:** [Kaggle — House Sales in King County, USA](https://www.kaggle.com/datasets/sumaya23abdul/house-sales-in-king-county-usa?utm_source=chatgpt.com)
- **File:** `kc_house_data.csv`
- **Rows:** Approximately 21,613
- **Target:** `price`
- **Task type:** Regression

## Definition of Done

By the end of the four-sprint capstone, the project will include:

- [ ] A clean, documented Jupyter Notebook covering EDA, preprocessing, modelling, and evaluation.
- [ ] Documented exploratory data analysis, including key data-quality findings and observations.
- [ ] A reproducible preprocessing pipeline.
- [ ] A baseline regression model and an improved-model comparison stage.
- [ ] Evaluation using appropriate regression metrics, including MAE, RMSE, and R².
- [ ] A final trained model with reported metrics.
- [ ] A working public deployment using Streamlit or FastAPI.
- [ ] A clean GitHub repository with a complete README and `requirements.txt`.
- [ ] A saved model artifact.
- [ ] A short technical write-up describing the approach, results, and limitations.

## Sprint 1 Goal

Understand the King County House Sales Dataset, perform exploratory data analysis, prepare the preprocessing approach, and establish a Linear Regression baseline for future model comparison.

## Sprint 1 Backlog

| # | Task | Description | Estimate | Acceptance criteria |
| --- | --- | --- | --- | --- |
| 1 | Dataset setup and documentation | Obtain the approved King County House Sales Dataset and record its source and target. | 30 min | Dataset source, file location, target (`price`), and intended use are documented in Markdown; raw data is kept in `data/raw/`; work is committed on the correct feature branch with a clear message; a PR is opened before merge. |
| 2 | Dataset inspection | Inspect dimensions, columns, data types, and a small sample to understand the dataset structure. | 1 hour | Dataset shape, column names, data types, and representative records are inspected; findings are documented in Markdown; notebook runs without errors; work is committed on the correct feature branch and proposed through a PR. |
| 3 | Data quality analysis | Identify missing values, duplicate rows, and obvious data-quality risks. | 1 hour | Missing values are quantified; duplicate rows are checked; relevant data-quality observations are documented in Markdown; notebook runs without errors; work is committed with a clear message and a PR is opened before merge. |
| 4 | Exploratory data analysis | Explore target distribution and important numeric and categorical features. | 2 hours | Target distribution is visualized; important numeric and categorical features are explored; key observations are documented in Markdown; notebook runs without errors; work is committed on the correct feature branch and reviewed by PR. |
| 5 | Define features and target | Identify `price` as the target and document the initial feature set and exclusions. | 30 min | Target and initial feature set are explicitly documented; any excluded columns have a stated reason; the selection is reproducible in the notebook; changes are committed clearly and submitted in a PR. |
| 6 | Define preprocessing approach | Plan handling for missing values, numeric features, categorical features, and train/test splitting. | 1 hour | Proposed preprocessing steps and their rationale are documented; numeric and categorical treatment is specified; the approach is recorded in Markdown without implementation; work is committed clearly and submitted in a PR. |
| 7 | Build baseline Linear Regression model | Create a simple Linear Regression baseline using the agreed Sprint 1 preparation approach. | 1.5 hours | Linear Regression trains successfully; notebook runs without errors; modelling choices and result are documented; work is committed on the correct feature branch and a PR is opened before merge. |
| 8 | Evaluate the baseline using regression metrics | Evaluate the baseline model and retain its metrics for later comparison. | 1 hour | MAE, RMSE, and R² are reported; results are documented; metrics are retained as the future comparison baseline; notebook runs without errors; work is committed clearly and submitted in a PR. |
| 9 | Document Sprint 1 findings | Summarize data understanding, data-quality findings, preprocessing decisions, and baseline result. | 1 hour | Sprint 1 findings, decisions, limitations, and next steps are documented in Markdown; baseline metrics are included; notebook runs without errors; documentation is committed clearly and reviewed through a PR. |

**Planned Sprint 1 effort:** 9.5 hours.

## Project Structure

```text
house-price-prediction/
├── data/
│   └── raw/
├── notebooks/
├── src/
├── models/
├── README.md
├── requirements.txt
└── .gitignore
```

The empty directories are intentionally retained for future Sprint 1 work. No dataset, notebook, source code, model, or deployment has been created during Day 5.

## Models

To be completed in future sprints.

## Evaluation

To be completed in future sprints.

## Deployment

To be completed in future sprints.

## Mentor Sign-Off

- Project selection: Pending approval
- Sprint 1 goal: Pending approval
