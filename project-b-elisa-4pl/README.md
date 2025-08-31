create project-b-elisa-4pl folder
# Project B: ELISA 4PL Analysis in R

This project recreates a classic **ELISA (Enzyme-Linked Immunosorbent Assay)** analysis workflow in R.  
Instead of Excel-based curve fitting, I built a reproducible pipeline that simulates ELISA data, fits a **4-parameter logistic (4PL) model**, and predicts unknown sample concentrations.

---

## What I did
- Simulated ELISA standard curve data with replicates and added experimental noise.  
- Aggregated replicates (mean ± SD).  
- Fit a 4-parameter logistic curve using the `drc` package.  
- Plotted the standard curve with error bars on a log10 axis.  
- Predicted concentrations of unknown samples by inverting the model.  
- Exported results as CSV and PNG for reporting.  

---

## Example output

Here is the fitted **4PL ELISA standard curve** with error bars and fitted line:  

![ELISA 4PL Curve](docs/elisa_curve.png)

---

## Project structure
project-b-elisa-4pl/
│
├── elisa4plproject.Rmd # RMarkdown notebook with full workflow
├── data/ # Simulated input data
│ ├── elisa_standards.csv
│ └── elisa_unknowns.csv
├── docs/ # Output results
│ ├── elisa_curve.png
│ └── unknowns_predicted.csv
└── README.md # Project description (this file)

yaml
Copy code

---

## Why this matters
ELISA is one of the most widely used assays in biomedical science.  
Automating the analysis in R makes the workflow **transparent, reproducible, and industry-ready** — valuable skills for both research and pharma.  

---

## Next steps
- Extend the workflow to a **5-parameter logistic (5PL)** model.  
- Import and analyse **real ELISA plate data**.  
- Build a **Shiny app** for interactive curve fitting and QC.
