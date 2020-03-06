# CA04 - Ensemble Models

CA04_EnsembleModels_Mohu.ipynb is a python 3.0 notebook program for building Ensemble Classification models predicting income of a person based on different feature variables to be above 50K or below 50K. We use Random Forest, AdaBoost, gradient bossting and XG boost techniques

# Data Source 

The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset: 

• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ] 

• Number of attributes (Columns): 7 • Number of instances (Rows): 48,842 
 
The data is provided in a .csv file. Download the data and other files for this assignment from the following GitHub link. https://github.com/ArinB/MSBA-CA-03-Decision-Trees 

# Installation Instructions

User must have Jupyter notebook installed or Google Colab notebook Python 3.0 environment 
The libraries required for this code are as follows:

import pandas as pd
import numpy as np
from sklearn.ensemble import RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier
from sklearn.metrics import accuracy_score
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier

from sklearn import datasets
import xgboost
from xgboost import XGBClassifier
from sklearn.metrics import roc_auc_score

# Running Instructions

User can download and run the .ipynb notebook from the CA04 folder in the repository BSAN6070-CA-SAH.
Inline comments have been provided to explain the several sections of the code

# Usage

The code is provided with detailed comments and text columns to provide clear understanding of building and evaluating perfromance of Ensemble modelsin machine learning. The python notebook is divided into different sections explaining what is happening in each part listed as follows:

1. Reading the Dataset

2. Data Preprocessing 

3. Create Dummy Variables

4. Split the Data into Training and Testing sets

5. Finding Optimal Value of a key Hyper-parameter

6. Building a Random Forest Model

7. Building AdaBoost, Gradiant Boost Classifier Model and XGB models

8. Compare Perfromance


# References 

References

[Learning Data Science ](https://itnext.io/learning-data-science-predict-adult-income-with-decision-tree-ae8dd57a76cc)

[Remove Special Characters from Column names for XGBOOST](https://stackoverflow.com/questions/33257344/how-to-remove-special-characers-from-a-column-of-dataframe-using-module-re)

[Machine Learning Ensemble Methods Presentation by Prof Arin Brahma]

[Stack overflow](https://stackoverflow.com/questions/18022845/pandas-index-column-title-or-name)

# Contributors 

Mohu Sah

Professor Arin Brahma who provided the instructions for Ensemble Models and pre processed and clean dataset to work on. 








