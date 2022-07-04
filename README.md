# Normative Modelling
This notebook performs normative modelling analysis on data from EU-AIMS consortium and Robert Debré Hospital (Paris) to study brain features in ASD.

## Data
Data includes cortical thickness, surface areas and demographic, clinical informations for all subjects. 

Note that autism scores are only available for EU-AIMS data. Description of these scores can be found in the data folder.  

## Modelling
This code runs warped Bayesian linear regression (BLR) from the 'PCNtoolkit' packages. 

Find PCNtoolkit BLR tutorial [here](https://pcntoolkit.readthedocs.io/en/latest/pages/BLR_normativemodel_protocol.html).

## Plot
Plots individual Z-Scores on normative trajectory as a function of age.

Use [matplotlib](https://matplotlib.org/) packages. 
## Clustering
Finds clusters in Z-Scores to stratify autism on normative cortical thickness with K-means and Gaussian mixture models.  

Use [scikit-learn](https://scikit-learn.org/stable/) packages. 

## Spearman's correlation
Computes correlation between Z-Scores and autism test scores for each cluster.

Use [scipy](https://scipy.org/) packages. 


## Brain maps
Maps atypicality based on Z-Scores across brain regions. 

Maps model evaluation metrics (e.g. Explained variance) across brain regions.


Use [enigmatoolbox](https://enigma-toolbox.readthedocs.io/en/latest/index.html) packages.

