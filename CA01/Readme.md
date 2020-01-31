# BSAN6070-CA-SAH

Data Exploration and Data Cleaning

### Tags

business, 
natural and physical sciences, 
india, 
green living and environmental issues, 
pollution

 # Data source
 
 India Air Qaulity Data - https://www.kaggle.com/shrutibhargava94/india-air-quality-data
 
### About this file: 

Combined data for Historical Daily Ambient Air Quality. 
The "date" column is the clean version of the "sampling_date" for the given observation.

### Columns in the Dataset: 

stn_code,
sampling_date,
stateState,
locationCity,
agency,
typeArea category,
so2Sulphur dioxde,
no2Nitrogen dioxide,

 
# Packages imported for analysis

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import datetime

from sklearn.impute import SimpleImputer

import seaborn as sns


# Running Instructions

Run the code as it is for Data cleaning and Exploratory analysis. Make sure that all the required packages are
installed and imported for analysis.

# Techniques Used in Data Exploration and Cleaning

## Functions Used 

data.shape() - It returns a number of rows and columns in a dataset

data.isnull() - It returns a number of null values in each column

data.info() - It returns range, column, number of non-null objects of each column, datatype and memory usage

data.count() - It results in a number of non null values in each column.

## Cleaning the Dataset

1. Dropping of less valued columns

2. Changing The types to uniform format

3. Creating a year column

4. Handling Missing values

5. Analysis of dtaa of particular state



## Author 

Mohu Sah

# References

https://www.kaggle.com/shrutibhargava94/india-air-quality-data

https://scikit-learn.org/stable/modules/generated/sklearn.impute.SimpleImputer.html
