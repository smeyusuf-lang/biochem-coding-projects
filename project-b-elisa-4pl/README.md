create project-b-elisa-4pl folder
# ELISA 4PL Analysis in R

This project demonstrates how to analyse data from an **Enzyme-Linked Immunosorbent Assay (ELISA)** using R.  
The workflow simulates experimental data, fits a **four-parameter logistic (4PL)** model, and predicts the concentration of unknown samples.

---

## Overview
ELISAs are widely used to quantify proteins, hormones, or other biomolecules.  
Data are often processed in Excel, but this approach can be difficult to reproduce and share.  
Here, the analysis is carried out entirely in R to ensure the workflow is transparent, reproducible, and version-controlled.

---

## Methods
- Simulated ELISA standards and unknowns with replicate noise.  
- Aggregated replicates (mean ± SD).  
- Fitted a 4PL curve using the `drc` package.  
- Visualised the standard curve on a log10 scale with error bars.  
- Estimated concentrations of unknown samples from the fitted model.  
- Exported results as `.csv` and `.png` for reporting.  

---

## Project Structure
```
project-b-elisa-4pl/
│
├── elisa4plproject.Rmd         # RMarkdown notebook
├── data/                       # Simulated raw data
│   ├── elisa_standards.csv
│   └── elisa_unknowns.csv
├── docs/                       # Results and outputs
│   ├── elisa_curve.png
│   └── unknowns_predicted.csv
└── README.md
```
yaml
Copy code

---

## Next Steps
- Extend to a 5-parameter logistic (5PL) model.  
- Import and process real ELISA plate-reader data.  
- Build a Shiny app for interactive fitting and QC.
