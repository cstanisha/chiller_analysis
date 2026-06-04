# 7F AHU Chiller Plant — Correlation & Anomaly Analysis

## About
Analysis of 7F Front Side AHU trend data (April 2026) covering Pearson correlation, 
anomaly detection, and temperature calculations.

---

## Data
Data files are shared via **Microsoft Teams** — not included in this repo.
Download and place in the same folder as the notebook before running.

---
## Key Finding
System fails every day between **10:00–11:30 AM** due to chiller capacity 
shortfall — not a controls fault.

## Setup
```bash
git clone https://github.com/yourusername/chiller_analysis.git
Create Virtal Environment 
pip install -r requirements.txt
```

Then open `chillerdata.ipynb` in VS Code and **Run All**.

---

- Introduced markdown cells explaining time series anomaly detection for evaporator leaving water temperature, including visualizations of anomalies and z-scores.
- Added insights on Pearson correlation analysis between all variables and evaporator leaving water temperature, highlighting key drivers and their significance.
- Included distribution analysis of evaporator leaving water temperature, confirming the effectiveness of z-score for anomaly detection.
- Enhanced correlation heatmap section with interpretations of multicollinearity among motor current parameters.
- Created a scatter matrix to visualize relationships between top drivers and the target variable, emphasizing the physical correlations.
- Developed operational efficiency diagnostics dashboard, detailing the chiller's performance and identifying anomalies in efficiency.
- Summarized findings in a final conclusion markdown, outlining key insights and recommendations for further investigation for commit 
