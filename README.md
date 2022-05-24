# Normative Modelling
This notebook performs normative modelling analysis on data from EU-AIMS consortium and Robert Debré Hospital (Paris) for ASD study.

## Data
Data includes cortical thickness/surface areas and demographic/clinical informations for all subjects. 

Note that autism scores are only available for EU-AIMS data. Description of these scores can be found in the data folder.  

## Modelling
This code runs warped Bayesian linear regression (BLR) from the 'PCNtoolkit' packages. 

Find PCNtoolkit BLR tutorial [here](https://pcntoolkit.readthedocs.io/en/latest/pages/BLR_normativemodel_protocol.html).

## Plot
Plots individual Z-Scores on normative trajectory as a function of age.

<p align="center">
  <img width="450" alt="image" src="https://user-images.githubusercontent.com/77856551/170001636-b5651722-6c43-43e6-ac88-1a442cfa4a85.png">
</p>

Use [matplotlib](https://matplotlib.org/) packages. 
## Clustering
Finds clusters in Z-Scores to stratify autism on normative cortical thickness with K-means and Gaussian mixture models.  
<p align="center">
  <img width="450" alt="image" src="https://user-images.githubusercontent.com/77856551/169999696-f2e3c5d4-bceb-4e81-bf00-f27db23c157d.png">
</p>

Use [scikit-learn](https://scikit-learn.org/stable/) packages. 

## Spearman's correlation
Computes correlation between Z-Scores and autism test scores for each cluster.

<p align="center">
  <img width="450" alt="image" src="https://user-images.githubusercontent.com/77856551/169999821-07907219-fa57-46ef-8920-1b93d04fad3a.png">
  
</p>
 

Use [scipy](https://scipy.org/) packages. 

## T-Tests
Perfoms case-control tests between ASD Z-Scores and TD Z-Scores.

Use scipy and [statsmodels](https://www.statsmodels.org/stable/index.html) packages.

## Brain maps
Maps atypicality based on Z-Scores across brain regions. 
<p align="center">
  <img width="450" alt="image" src="https://user-images.githubusercontent.com/77856551/170000089-9a397df1-0d7c-4690-b622-84cdb54b357b.png">

</p>

Maps model evaluation metrics (e.g. Explained variance) across brain regions.

<p align="center">
  <img width="450" alt="image" src="https://user-images.githubusercontent.com/77856551/170002406-ef57ca1c-f330-457d-b914-48a031dc2d5a.png">
</p>

Use [enigmatoolbox](https://enigma-toolbox.readthedocs.io/en/latest/index.html) packages.

