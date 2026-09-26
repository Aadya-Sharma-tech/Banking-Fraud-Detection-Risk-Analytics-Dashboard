# Banking-Fraud-Detection-Risk-Analytics-Dashboard
A Power BI fraud-monitoring dashboard analyzing transaction risk patterns, flagging anomalies via DAX-driven KPIs and drill-through investigation views, simulating real-world fraud analyst workflows.

Dataset link - https://www.kaggle.com/datasets/deepeshkansotia/banking-fraud-detection-and-risk-analytics-dataset?resource=download

## Financial Fraud Analytics Framework
### 🟦 Layer 1 — Descriptive Analytics
- Core Question: What happened?
  -  Objective: Summarize historical data to establish baseline performance and quantify overall fraud occurrence.
- Key Focus Areas:
  - Total transaction volume versus total fraudulent transactions.
  - Overall fraud rate across the entire dataset.
  - Total financial loss incurred due to fraud.
- Baseline metrics for transaction amounts, device risk scores, and login attempt counts.

## 🟨 Layer 2 — Diagnostic Analytics
- Core Question: Why did it happen / What patterns are associated with it?
  - Primary Objective: Examine underlying patterns, correlations, and feature combinations to understand fraud behavior.
- Key Focus Areas:
  - Behavioral profile comparison (e.g., comparing legitimate vs. fraudulent transaction features side-by-side).
  - Risk factor correlation (e.g., investigating how device risk, suspicious IPs, or anomaly scores relate to fraud likelihood).
  - Threshold identification (e.g., determining at what exact amount or login count fraud rates surge).
- Multi-signal interactions (e.g., evaluating high-risk combinations like high device risk + international location + suspicious IP).

## 🟥 Layer 3 — Predictive Analytics
- Core Question: What might happen in the future?
  - Primary Objective: Build and evaluate machine learning models to classify new, incoming transactions in real time.
- Key Focus Areas:
  - Target definition (binary classification where 0 = Legitimate, 1 = Fraudulent).
  - Model selection (experimenting with algorithms such as Logistic Regression, Random Forest, XGBoost, or LightGBM).
  - Feature importance ranking (identifying which features contribute most heavily to risk prediction).
- Performance evaluation (measuring model effectiveness using precision, recall, F1-score, and ROC-AUC).

- <img width="902" height="507" alt="image" src="https://github.com/user-attachments/assets/e8c6dcc8-4fdf-4810-a77f-578e8f556556" />

<img width="903" height="509" alt="image" src="https://github.com/user-attachments/assets/d9acb9af-bd6e-42bb-a0b0-9cd4eae738e4" />

<img width="900" height="507" alt="image" src="https://github.com/user-attachments/assets/bd0e6172-5eb5-4dad-8b84-46dceed1bc03" />



