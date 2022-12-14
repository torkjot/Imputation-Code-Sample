# Imputation Code Sample

This repository outlines the method I used to impute missing river temperatures. The imputation work was done to prevent the exlcusion of data due missing environmental metadata. In order to calculate estimated river temperatures, I found the relationship between air and river temperatures using a general linear regression with pymc. This was part of a larger analysis for age-at-maturity modelling in juvenile parr. [To check out the code click here!](https://github.com/torkjot/Imputation-Code-Sample/blob/main/CodeSample_Imputation.ipynb)

## Directory
- DFO_CodeSample_Imputation.ipynb: Main notebook featuring code and narrative explanation of purpose, methods, and visualization
- Air_temperatures_blank.csv: The air temperatures from the FROST API by date
- River_temperatures_blank.csv: In-situ monitoring program river temperatures by date
- ReadME.md: You're actually reading it!
- git attributes and ignore files
