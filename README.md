# Thesis_MaStat
This repository contains the code for my MaStat thesis.

author: Michiel Van Nieuwenhove \
Promotor 1: prof. dr. Robby De Pauw [Sciensano] \
Promotor 2: dr. Charline Maertens de Noordhout [KCE]

## Summary of the research (Abstract)
This thesis builds on the NEED team’s research, which aims to populate a database of health-related needs and corresponding indicators to identify unmet needs across
various diseases. The NEED database includes both quantitative and qualitative data,
each requiring different analytical approaches. The goal of this work was twofold:
first, to compare needs and diseases using the quantitative data, and second, to differentiate the qualitative data based on their urgency scores. This thesis investigates
to what extent these objectives can be met, and where key challenges arise. The main
difficulty was the limited and unlabeled nature of the available data. While some insights were obtained, the primary contribution of this work lies in identifying which
methods show promise for future analysis, and what additional data or preprocessing
would be necessary to more effectively address both objectives.

## Structure
**Data**: contains the used data (NEED dataset [1], and GBD disability weights [2])
**Initial_Data_analysis**: This contains an extensive analysis of the NEED dataset in R.
**Further_Analysis_of_Values**: Consists of an R-project, extracting some extra analysis from the dataset, important to the implementation.
**Py_Notebooks**: This folder has all notebook files, trained models, and environment specifications. The analysis for the disability weights dataset is also shown here, in python.

## Technical Information
* The notebooks use Python 3.9.5, libraries used are found at 'Py_notebooks/env/Requirements.txt'.
* The data analysis is done in R 4.4.3, the used packages are:
  * ggplot2_3.5.2
  * stringr_1.5.1
  * tidyr_1.3.1
  * openxlsx_4.2.8 dplyr_1.1.4
  * arrow_19.0.1.1
  * knitr_1.50
  * readr_2.1.5
  * purrr_1.0.4
  * readxl_1.4.5

## References
**[1]** NEED collaborators, Unmet health-related needs for three selected health conditions in belgium (v2024-10-10) [data set], Zenodo, 2024. [Online]. Available: https://doi.org/10.5281/zenodo.12749982. \
**[2]** R. Burstein, T. Fleming, J. Haagsma, J. A. Salomon, T. Vos, and C. J. Murray, “Estimating distributions of health state severity for the global burden of disease study,” Population Health Metrics, vol. 13, no. 1, Nov. 2015. DOI: 10 . 1186 / s12963-015-0064-y.
