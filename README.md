# Net Metabolic Power & Step Length Asymmetry Analysis 🏃‍♂️📊

## Overview
This repository contains an **R-based pipeline** designed for **split-belt walking motor adaptation**. 
The script:
- Computes **steady-state resting metabolic rate (RMR)** from a standing trial.
- Estimates **steady-state walking net metabolic power** using the Peronnet & Massicotte equation.
- Computes **step length asymmetry (SLA)** based on treadmill perturbations.
- Applies **advanced statistical modeling**, including **Bayesian regression, mixed-effects modeling, and principal component analysis (PCA)**.

## Advanced Statistical Modeling
This pipeline integrates **statistical techniques** to analyze metabolic and asymmetry data:
- **Bayesian Regression (`brms`)**: Provides probabilistic estimates for **SLA's effect on net metabolic power**.
- **Mixed-Effects Modeling (`lme4`)**: Controls for **participant variability**, improving statistical power.
- **Principal Component Analysis (`factoextra`)**: Identifies dominant patterns across **Step Time Asymmetry (STA), Step Length Asymmetry (SLA), Double Support Asymmetry (DSA), and Propulsive Force Asymmetry (PFA)**.

## Dependencies
- **R version 4.0+**
- Required packages: `tidyverse`, `dplyr`, `lme4`, `brms`, `bayestestR`, `factoextra`, `ggplot2`
