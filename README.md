# Normative Modelling
This notebook performs normative modelling analysis on data from EU-AIMS consortium and Robert Debré Hospital (Paris). 

## Data
Data includes cortical thickness and demographic/clincal informations for all subjects. 

## Modelling
This code runs Bayesian linear regression with likelihood warping from the 'PCNtoolkit' packages https://pcntoolkit.readthedocs.io/en/latest/pages/BLR_normativemodel_protocol.html 

## Plot
Plots individual Z-Scores on normative trajectory. 

## Clustering
Finds clusters in Z-Scores to stratify autism on normative cortical thickness. 

## Spearman's correlation
Computes correlation between Z-Scores and autism test scores.

## T-Tests
Perfoms case-control tests between ASD Z-Scores and TD Z-Scores.

## Brain maps
Maps atypicality based on Z-Scores across brain regions. 
Maps model evaluation metrics (e.g. Explained variance) across brain regions.
