# Msc_Dissertation
# A Data-Driven Comparative System for City Hierarchies
This repository contains the code and processed data used to reproduce the
analyses presented in the MSc Data Science Extended Research Project,
"A Data-Driven Comparative System for City Hierarchies: A Multidimensional Framework Based on 56 Functional Urban Areas".
# Repository Structure
code: Python notebooks used for data processing and analysis.
data: processed datasets used as inputs for the analyses.
technical_appendix: detailed information on the analytical and reproducibility workflow.
# Analysis Workflow
The main analytical workflow is:
1. Data preparation and harmonisation
2. Variable transformation and standardisation
3. Construction of dimension scores and the Urban Hierarchy Index (UHI)
4. Tier classification
5. Relative Dimension Profile construction and Archetype classification
6. Robustness and sensitivity analyses
7. Projection of external cities onto the reference framework
Except for Step 7, which is completed in the Dashboard, the code files corresponding to Steps 1–6 are organised sequentially according to the analytical workflow described above.
# Data
The repository contains processed data required for the analyses. The original source data are not redistributed in this repository. Information on data sources, definitions and processing procedures is provided in the dissertation and technical appendix.
# Software Requirements
The analyses were conducted in Python.
Main packages include: pandas, numpy, scipy, scikit-learn, matplotlib
The dashboard was developed and implemented using ArcGIS Experience Builder.
# Reproducing the Analysis
1. Download or clone this repository.
2. Install the required Python packages.
3. Run the code files in the order indicated by their filenames.
4. Detailed parameter settings and analytical procedures are documented
   in the technical appendix.
# Notes
The submitted code retains the original local file paths used during the analysis. Users may need to update these paths to match their own local directory structure before running the code.
