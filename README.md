# Kaggle Playground Series S5E5 — Predict Calorie Expenditure

This repository contains my solution notebook for the Kaggle Playground Series **Season 5, Episode 5** competition: **Predict Calorie Expenditure**.

The goal is to build a regression model that predicts **calories burned** during a workout based on demographic and physiological features.

---

## Project Highlights

- End-to-end workflow in a single notebook:
  - Data loading & sanity checks
  - Exploratory Data Analysis (EDA)
  - Feature preparation (basic preprocessing/encoding as needed)
  - Model training (tree-based regression; includes CatBoost artefacts)
  - Local validation and submission generation
- Competition metric: **RMSLE** (as used by the competition)

---

## Repository Structure

- `kaggle_s5e05.ipynb` — Main notebook (EDA → training → submission)
- `train.csv` — Training dataset (features + target)
- `test.csv` — Test dataset (features only)
- `sample_submission.csv` — Kaggle sample submission format
- `submission.csv`, `submission_2.csv` — Generated submissions
- `calories.csv` — Additional data file used in the workflow (if applicable)
- `catboost_info/` — Training artefacts/logs from CatBoost runs

