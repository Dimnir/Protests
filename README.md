## General info
This project is about building simple model to predict a successful protest. <br />
Using python (libraries: NumPy, Pandas, Matplotlib, sklearn ..) analysing a dataset of protests and trying to find factors which make protests achieve their final goals.

## Description
Datasets used:
  - ['NAVCO 2.1 Dataset'](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/MHOXDV) - Nonviolent and Violent Campaigns and Outcomes
  - ['World Population 1960-2018'](https://www.kaggle.com/imdevskp/world-population-19602018) - Population of each country, 1960-2018

## Content

+ #### `Variables.pdf` <br /> 
Information on used variables.

+ #### `ViolenceAndSuccess.ipynb` <br />
 __Main objective :__ See whether violence contributes to the success rate of protests.  <br />
 In this notebook we see the relationship between violent / non-violent protests and their success.
 
+ #### `SizeAndSuccess.ipynb` <br />
 __Main objective :__ See whether larger protests are more likely to succeed.  <br />
 In this notebook we see the relationship between the size of a protest and its success. <br />
 Comparing the protests in the dataset with the George Floyd and BLM movement worldwide protests to see differences. <br />

+ #### `ProtestSuccessPrediction.ipynb` <br />
__Main objective :__ Build a model to predict a successful protest. <br />
In this notebook we see an attempt to build a model which predict if a protest was successful or failed. <br />
Using logistic regression, predicting the success of a protest, based on violence and size greater than 3% of pop. <br />

