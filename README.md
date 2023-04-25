# EDA and Feature Engineering on Black Friday Sales Dataset

This repository contains EDA as well as feature engineering on the Black Friday Sales dataset. The purpose of this project is to explore and analyze the Black Friday Sales dataset using various charts and make the data ready for 
model training.

# Dataset
The dataset consists of two files, the 'train.csv' and the 'test.csv'. It contains various information of the
customer such as Age, Gender, Occupation, Product Category etc. The combined (train + test) dataset contains 783667 rows and 12 columns.

# Requirements

To run this project, you will need the following packages:

pandas numpy matplotlib seaborn sklearn

# Usage

To run the EDA, simply run the black_friday_sales.ipynb file in a Jupyter notebook or JupyterLab environment. The notebook contains the code used to explore and analyze the dataset, along with explanations and visualizations of the results.

# Data Pre-processing and Visualization
1. To perform preprocessing on the data, the train and test data have been merged. 
2. The categorical values have been converted to numerical formats and null values have been replaced with mode of the column. 
3. Data Visualization is performed with bar charts and observations are noted
4. Feature scaling is performed and data is ready for model training.

# References

Krish Naik's Black Friday Dataset tutorial: (https://youtu.be/fHFOANOHwh8?t=3584)
