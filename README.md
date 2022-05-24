# Normative Modelling
This notebook performs normative modelling analysis on data from EU-AIMS consortium and Robert Debré Hospital (Paris) for ASD study.

## Data
Data includes cortical thickness and demographic/clinical informations for all subjects. 

Note that Autism scores are only avaible for EU-AIMS data. 

## Modelling
This code runs warped Bayesian linear regression (BLR) from the 'PCNtoolkit' packages. 

Find PCNtoolkit BLR [tutorial](https://pcntoolkit.readthedocs.io/en/latest/pages/BLR_normativemodel_protocol.html).

Installation of PCNtoolkit here: https://github.com/amarquand/PCNtoolkit 

## Plot
Plots individual Z-Scores on normative trajectory as a function of age.

Use [matplotlib](https://matplotlib.org/) packages. 
## Clustering
Finds clusters in Z-Scores to stratify autism on normative cortical thickness. 

Use [scikit-learn](https://scikit-learn.org/stable/) packages. 

## Spearman's correlation
Computes correlation between Z-Scores and autism test scores. 

Use [scipy](https://scipy.org/) packages. 

## T-Tests
Perfoms case-control tests between ASD Z-Scores and TD Z-Scores.

Use scipy and [statsmodels]( https://www.statsmodels.org/stable/index.html) packages.

## Brain maps
Maps atypicality based on Z-Scores across brain regions. 
Maps model evaluation metrics (e.g. Explained variance) across brain regions.

Use [enigmatoolbox](https://enigma-toolbox.readthedocs.io/en/latest/index.html) packages.

