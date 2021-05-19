# machine-learning-challenge

![](Images/exoplanets.jpg)

Over the previous decade, , the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. this search for exoplanets have been among the most exciting topic in contemporary astrnomy; and NASA's Kepler program has provided the means to advance this field further than previously thought possible. 
The elegant logic behind Kepler's methodology is that Exoplanets have no light of their own, and their transit in front of their home stars would cause a small barely perceptible drop in the stars' light emissions. 
This methodology has led to large quantities of image data  covering hours of observations waiting for the chance that a distant star  might  register a tell-tale blip in its light emissions. 

## the-exoplanet-dataset

Data from the Kepler telescope has been maintained, updated, and released to the public through the Kepler exoplanet dataset which is documented in [this link](https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html) One might notice that many columns in this dataset do not make sense without the accompanying documentation. One might also notice the large number of columns which complicates the use of simpler, more popular traditional techniques. In machie learning, multivariate statistics is employed to solve this problem. 

## multivariate_statistics

There are many uses for multivaruate statistics on complex datasets:
1. One might prefer traditional multiple regression to obtain coefficients that approcimate predicted change according to changes in certain features. 
2. Others might prefer to use multivariate techniques to rliminate features so that only the most relevant dimensions are retained in a dataset. 

These approaches are not necessarily mutually exclusive as traditional multivariate statistics also employs some form of feature elimination. The difference with modern data science is that machine learning enables the computer to perform feature elimination instead of relying on human discretion. Use case 1 is best for estimating how the manipulation of one predictor might affect the criterion variable; while use case 2 is best for reducing a large number of predictors to just a few significant ones. Use case 1 might be more familiar as "Multiple Regression" while use case two is often demonstrated in techniques such as "Primary Component Analysis" or PCA, and Recursive Feature Elimination (RFE).  

## Precision-vs-Recall

Inferential statistics has traditionally used the terms "Type I error" and "Type II error"; but Data Science prefers has its own jaargon and makes use of "Precision" and "Recall". Precision reflects theproportion of predictions made by a machine learning model made up of true positives. Recall is the prportio of potential positives correctly identified by a machine learning model. In short, Precision measures the incdence of Type I errors or incorrect identifications; while Recall measuresmeasures the incidence of Type II errors or incorrect rejections. Any machine learning model will be 
