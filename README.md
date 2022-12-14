# Imputation Code Sample
 
## Directory
- git attributes and ignore files
- Air_temperatures_blank.csv: The air temperatures from the FROST API by date
- River_temperatures_blank.csv: In-situ monitoring program river temperatures by date
- DFO_CodeSample_Imputation.ipynb: Main notebook featuring code and narrative explanation of purpose, methods, and visualization
- ReadME.md: You're actually reading it!

## Outline of Notebook
Please check out my Jupyter Notebook [linked here](https://github.com/torkjot/Imputation-Code-Sample/blob/main/CodeSample_Imputation.ipynb)!


This notebook outlines the method used to impute missing river temperatures based on air temperatures. This is part of a larger analysis for age-at-maturity modelling in juvenile parr. This imputation work was done to prevent the exlcusion of data due to holes in the environmental meta data. In order to calculate estimated river temperatures, I find the relationship between air and river temperatures using a general linear regression. 
