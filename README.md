# 🕵️ Fraud Hunter

An anomaly detection project exploring class imbalance, supervised and unsupervised fraud detection, and model explainability on e-commerce transaction data.

> **Status: In Progress** — Project setup complete. Data understanding starting.

## Overview

- **Class Imbalance Handling** — working with a heavily skewed fraud/non-fraud distribution
- **Supervised Detection** — classification models (Logistic Regression, Random Forest, XGBoost)
- **Unsupervised Detection** — Isolation Forest for anomaly detection
- **Explainability** — SHAP-based explanations for individual predictions

> Dataset not included in this repo — see notebooks for source and setup.

## Roadmap

- [ ] Day 1 — Data understanding, sampling, and class imbalance EDA
- [ ] Day 2 — Feature engineering
- [ ] Day 3 — Classification models (Logistic Regression, Random Forest, XGBoost)
- [ ] Day 4 — Isolation Forest anomaly detection
- [ ] Day 5 — SHAP explainability + dashboard

## Tech Stack

Python · Pandas · NumPy · Scikit-learn · XGBoost · SHAP · Matplotlib · Seaborn · Jupyter

## Project Structure

```
fraud-hunter/
├── data/raw/
├── notebooks/
├── src/
├── app/
└── requirements.txt
```

## Running Locally

```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/
```

---
*Project 3 of 4 in a 20-day AI + Data Science portfolio program: Retail Radar → Moodify AI → Fraud Hunter → AI Decision Lab.*