# Logistic Regression & XGBoost for Risk-Based Credit Analysis

## Project Overview

This project investigates the following research question:

> **"Can machine learning models accurately predict loan default risk, and how can these predictions support risk-based lending decisions?"**

Using Prosper loan data, the project develops a credit default risk analysis framework that goes beyond prediction by incorporating risk segmentation, expected loss analysis, and threshold-based lending decisions.

---

## Key Results

| Metric | Logistic Regression | XGBoost |
|---|---:|---:|
| ROC-AUC | 0.716 | **0.771** |
| Default Precision | 0.60 | **0.67** |
| Default Recall | 0.24 | **0.35** |
| Default F1 | 0.34 | **0.46** |
| KS Statistic | - | **0.396** |

XGBoost achieved stronger predictive performance than Logistic Regression and was therefore used for the subsequent risk analysis.

---

## Project Workflow

```text
Data Preparation
       ↓
Default Risk Prediction
       ↓
Model Evaluation
       ↓
Probability Calibration
       ↓
Model Explainability
       ↓
Risk Segmentation
       ↓
Expected Loss Analysis
       ↓
Threshold Analysis
       ↓
Approve / Reject Decision
