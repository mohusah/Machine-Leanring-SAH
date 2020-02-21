# CA03 - Decision Tree Algorithm 

CA03_Decisiontree_Mohu.ipynb is a python 3.0 notebook program for predicting income of a person based on different feature variables to be above 50K or below 50K using Decision Tree Classification Algorithm.

# About Dataset 

The dataset is obtained from the Census Bureau and represents salaries of people along with seven demographic variables. The following is a description of our dataset: 

• Number of target classes: 2 ('>50K' and '<=50K') [ Labels: 1, 0 ] 

• Number of attributes (Columns): 7 • Number of instances (Rows): 48,842 
 
The data is provided in a .csv file. Download the data and other files for this assignment from the following GitHub link. https://github.com/ArinB/MSBA-CA-03-Decision-Trees 

# Installation Instructions

User must have Jupyter notebook installed or Google Colab notebook Python 3.0 environment 
The libraries required for this code are as follows:

import pandas as pd
import numpy as np
from sklearn import tree
import graphviz
from sklearn.model_selection import cross_val_score
import matplotlib.pyplot as plt
from sklearn.tree import DecisionTreeClassifier

### For Visualization import the following libraries
from sklearn.externals.six import StringIO  

from IPython.display import Image  

from sklearn.tree import export_graphviz

import pydotplus

import graphviz

### For Performance metrics import the following directories:

from sklearn.metrics import classification_report,confusion_matrix,accuracy_score,precision_recall_fsco

from sklearn.metrics import roc_auc_score

from sklearn.metrics import plot_roc_curve


# Running Instructions

User can download the .ipynb notebook from the link mentioned in the code as well as above. The File 'Tree Tuning Cases' is provided in the Github repository and can be downloaded from there and uploaded in your notebook. 
The dataframe for prediction will be created in the last section as a csv file. 

Run the code as it is after uploading the ecessary files. Inline comments have been provided to explain the several sections of the code

# Usage

The code is provided with detailed comments and text columns to provide clear understanding of building a Decision Tree Classification model. The python notebook is divided into different sections explaining what is happening in each part listed as follows:

1. Reading the Dataset

2. Split the columns 

3. Exploratory Data Analysis - Bar Charts, Descriptives

4. Create Dummy Variables

5. Split the Data into Training and Testing sets

6. Fit and Visualize Decision Tree

7. Hyper Parameter Tuning 

8. Automation of Perfromance metrics

9. Predicting the income of a person


# References 

References

[Learning Data Science ](https://itnext.io/learning-data-science-predict-adult-income-with-decision-tree-ae8dd57a76cc)

[Decision Trees Sckit Learn](/https://scikit-learn.org/stable/modules/tree.html#tree-algorithms-id3-c4-5-c5-0-and-cart)

[Decision Tree Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier)

[Stack overflow](https://stackoverflow.com/questions/45376410/how-to-get-roc-curve-for-decision-tree)

# Contributors 

Mohu Sah

Professor Arin Brahma who provided the instructions for DEcision Tree Building Algorithm and pre processed and clean dataset to work on. 







