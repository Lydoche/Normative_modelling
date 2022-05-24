# Normative Modelling
This notebook performs normative modelling analysis on data from EU-AIMS consortium and Robert Debré Hospital (Paris). 

## Data
Data includes cortical thickness and demographic/clincal informations for all subjects. 

## Modelling
This code runs Bayesian linear regression (BLR) with likelihood warping from the 'PCNtoolkit' packages. 

PCNtoolkit BLR tutorial: https://pcntoolkit.readthedocs.io/en/latest/pages/BLR_normativemodel_protocol.html 
Installation of PCNtoolkit here: https://github.com/amarquand/PCNtoolkit 

## Plot
Plots individual Z-Scores on normative trajectory. 

Use *matplotlib* packages: https://matplotlib.org/
## Clustering
Finds clusters in Z-Scores to stratify autism on normative cortical thickness. 

Use *scikit-learn* packages: https://scikit-learn.org/stable/

## Spearman's correlation
Computes correlation between Z-Scores and autism test scores.

Use *scipy* packages: https://scipy.org/

## T-Tests
Perfoms case-control tests between ASD Z-Scores and TD Z-Scores.

Use *scipy* and *statsmodels* packages: https://www.statsmodels.org/stable/index.html

## Brain maps
Maps atypicality based on Z-Scores across brain regions. 
Maps model evaluation metrics (e.g. Explained variance) across brain regions.

Use *enigmatoolbox* packages: https://enigma-toolbox.readthedocs.io/en/latest/index.html 


