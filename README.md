## Introduction
This Project was from my one of the classes from USC Marshall School of Business, DSO 562 - Fraud Analytics. It is an unsupervised machine learning problem where we were told to identify the outliers in the NYC Property valuation datatset who follow wrong practices in property tax filing. Principal component analysis and Autoencoder were used to solve the problem after proper handling of missing values and feature engineering.

## Repositiory File description
I've included the code I created as well as the data quality report I made for the project in this. 
Dataset Name: Property Valuation and Assessment Data Dataset Source: Open data of NYC government Dataset URL: https://data.cityofnewyork.us/Housing-Development/Property-Valuation-andAssessment-Data/rgy2-tti8 Time Period: November 2010 No. of Fields: 32 No. of Records: 1,070,994

Summary
The main indicators of property tax fraud were property tax assessments that were too high or too low. Given a property dataset of 1,070,994 records and 32 data fields, we first described, visualized, and filled in missing values for each variable. Second, 45 additional variables were created in order to create the most accurate algorithm. Next, we used dimensionality reduction techniques to refine our dataset. Finally, we used Principal Component Analysis (PCA) to limit correlating variables and then used 2 algorithms to obtain fraud scores. The two algorithms were an autoencoder as well as a calculating error-values from the median with z-scaling. The scores were combined and then ranked to get a final fraud score. I additionally played around with a few various types of ways of ranking error at the end too. 

How to run the code
Just download the notebook into your system along with the dataset given in the link.
Then import the data and replace it with the one which was previously imported
