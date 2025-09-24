# Project A: Dose–Response Modelling

## Overview
A Python project exploring how cancer drugs vary in potency across different cell lines.  
I simulated dose–response data for two different cancer treatments:  
- **EGFR inhibitor** (lung cancer)  
- **Hormone therapy** (breast cancer)  

Tested across two cell lines:  
- **A549** – lung adenocarcinoma  
- **MCF7** – breast adenocarcinoma  

---

## Key Results
- EGFR inhibitor was more potent in lung cells (A549).  
- Hormone therapy was more potent in breast cells (MCF7).  
- Replicates were added to capture variability.  
- IC50 values were estimated and compared in a summary chart.  

---

## Why It Matters
IC50 is a standard measure of drug potency. This project shows how coding can be used to analyse dose–response data and highlight context-specific activity, reflecting the idea of precision oncology.  

---

## Next Steps
- Apply the pipeline to real datasets (e.g. GDSC, CellMiner).  
- Explore curve fitting with the 4-parameter logistic model.  
