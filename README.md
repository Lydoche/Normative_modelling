# Normative Modelling
This notebook performs normative modelling analysis on data from EU-AIMS consortium and Robert Debré Hospital (Paris) to study brain features in ASD.

## Data 
Data includes cortical thickness / surface areas and demographic / clinical / genetic informations for each subject. 

## Model fit
This code runs warped Bayesian linear regression (BLR) from the 'PCNtoolkit' packages. 

Find PCNtoolkit BLR tutorial [here](https://pcntoolkit.readthedocs.io/en/latest/pages/BLR_normativemodel_protocol.html).

## Plot
Plots individual measures on normative trajectory as a function of age, stratified by sex.

Uses [matplotlib](https://matplotlib.org/) packages. 
## Clustering
Finds clusters in Z-Scores to stratify autism on normative cortical thickness with K-means and Gaussian mixture models.  

Uses [scikit-learn](https://scikit-learn.org/stable/) packages. 

## Spearman's correlation
Computes correlation between Z-Scores and autism test scores for each cluster.

Uses [scipy](https://scipy.org/) packages. 


## Brain maps
Maps atypicality based on Z-Scores across brain regions. 

Maps model evaluation metrics (e.g. Explained variance) across brain regions.


Uses [enigmatoolbox](https://enigma-toolbox.readthedocs.io/en/latest/index.html) packages.

