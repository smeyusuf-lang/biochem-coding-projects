# Biochem Coding Projects

This repository is a portfolio of coding projects where I combine **biochemistry** with **data science**. Each folder contains a focused project demonstrating how I analyse biological or chemical data using Python and R. The projects reflect my interests in drug discovery, assay analysis and cheminformatics.

## Projects

### Drug Response Analysis  
Fits dose–response curves to pharmacology data to estimate IC₅₀/EC₅₀ values. Uses non-linear regression models in R (tidyverse + nls), bootstrapped confidence intervals for parameters, and generates publication-quality plots of curve fits and residuals. Example data included with clear steps to run the analysis.

### ELISA 4-Parameter Logistic Fit  
Implements a four-parameter logistic model (4-PL) for ELISA standard curves. Calculates sample concentrations from absorbance values, includes QC checks such as replicate CV%, and generates calibration curves and diagnostic plots. Written in R, with a lightweight Python version planned.

### Cheminformatics Property Prediction  
Uses RDKit and scikit-learn to explore molecular properties. Computes basic descriptors (MolWt, LogP, HBD, HBA, TPSA), trains a simple regression model to predict solubility (ESOL data), evaluates model with MAE and RMSE metrics, and produces error and parity plots to visualise predictions.

