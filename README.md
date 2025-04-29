# Aircraft Risk Analysis for Portfolio Diversification

## Table of Contents
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Deliverables](#deliverables)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Technical Details](#technical-details)
- [Installation & Usage](#installation--usage)
- [Repository Structure](#repository-structure)


---

## Project Overview
A data-driven analysis to identify low-risk aircraft for commercial and private operations, supporting strategic decision-making for a company expanding into aviation. Combines statistical modeling, risk assessment, and business-focused visualizations.

---

## Problem Statement
**Business Challenge:**  
The company lacks aviation expertise and needs to:  
- Assess risks associated with purchasing aircraft  
- Prioritize aircraft models with favorable safety records  
- Minimize operational/financial risks in a new industry  

**Analytical Objective:**  
Identify aircraft with:  
✅ Lowest accident rates  
✅ Strong maintenance history  
✅ Cost-effective operational profiles  

---

## Deliverables
1. **`risk_analysis.ipynb`** (Jupyter Notebook)  
   - Data cleaning and preprocessing  
   - Risk metric calculations (e.g., accident rates, maintenance costs)  
   - Statistical modeling and aircraft ranking  

2. **`Aircraft_Risk_Dashboard.twb`** (Tableau)  
   - Interactive visualization of risk metrics  
   - Aircraft comparison tool  
   - Key performance indicator (KPI) summaries  

3. **`Aircraft_Acquisition_Strategy.pptx`** (PowerPoint)  
   - Executive summary of findings  
   - Actionable purchasing recommendations  
   - Risk mitigation strategies  

---

## Data Sources
| Source | Description | Relevance |
|--------|-------------|-----------|
| [NTSB Aviation Accident Database](https://www.ntsb.gov/) | Accident/incident reports | Safety risk assessment |
---

## Methodology
1. **Risk Factor Identification**  
   - Safety: Accident frequency, severity  
   - Operational: Age, usage patterns  

2. **Analytical Approach**  
   - Normalized risk scoring system  
   - Comparative analysis by aircraft category (commercial vs. private)   

3. **Visualization Strategy**  
   - Tableau dashboards for dynamic filtering  
   - Risk-reward matrices   

---

## Technical Details
**Tools Used**  
- Python (Pandas, NumPy, Scikit-learn)  
- Tableau Public  
- Jupyter Notebook  
- Microsoft PowerPoint  

**Dependencies**  
- See `requirements.txt` for Python libraries  

---

## Installation & Usage
1. **Jupyter Notebook**  
   ```bash
   pip install -r requirements.txt
   jupyter notebook risk_analysis.ipynb