FBMSP Case Study and Numerics

This repository contains an:
1. Case_Study_Code.Rmd - An R Notebook that produces the figures and
tables associated with Section 5: Case Study — Setting Mortgage Interest
Rates from the Feature-Based Market Segmentation & Pricing (FBMSP)
research.
2. Fig.3.Rmd - An R Notebook that produces Figure 3
3. Fig.4.Rmd - An R Notebook that produced Figure 4
4. HMDA.csv - A csv file that contains the data downloaded from the Home Mortgage Disclosure Act (HMDA) website, https://ffiec.cfpb.gov/ in 2020. 

Overview

The notebook demonstrates a case study using mortgage interest rate
data. It walks through: - Loading and cleaning the Home Mortgage
Disclosure Act (HMDA) dataset.
- Preprocessing steps for filtering relevant observations.
- Statistical modeling and evaluation of mortgage interest rate setting.
- Generating figures and tables for analysis.

Requirements

The notebook is written in R (tested with version R 4.5.0). The following
packages are required:

-   dplyr
-   AER
-   ggplot2
-   pROC
-   plotROC
-   caTools
-   ROCR
-   arm

Install them via:

    install.packages(c("dplyr", "AER", "ggplot2", "pROC", "plotROC", "caTools", "ROCR", "arm"))

Data

-   Input: data/HMDA.csv
    This is the Home Mortgage Disclosure Act (HMDA) dataset from 2020.
    Make sure the CSV is located in the data/ directory before running
    the notebook.

Running the Notebook

1.  Open Case_Study_MH.Rmd in RStudio (or your preferred R Markdown
    environment).
2.  Knit the notebook to produce HTML/PDF output, or run each code chunk
    interactively.
3.  The notebook will generate all figures and tables referenced in the
    case study.

Output

-   Cleaned and filtered HMDA dataset.
-   Regression and classification models estimating mortgage interest
    rates.
-   Visualizations (ROC curves, comparative plots, etc.).
-   Tables summarizing results used in the paper.

Citation

If you use this notebook or adapt its methods, please cite the
associated paper:

Cui, T., & Hamilton, M. (2022). Optimal Feature-Based Market Segmentation and Pricing. Available at SSRN 4151103.


