# Logistic Regression
## Using Admissions Data 
* This notebook explores classification methods with Logistic Regression Models using the Scikit-Learn library in order to predict probabilities of college admittance.
* The dataset utilized contains binary information indicating whether or not a student was admitted in addition to other features such as GRE scores, GPA, and prestige.

## Overview

### Introduction

### Predicting Binary Classes
- Comparing/contrasing Linear Regression and Logistic Regression Models
- Describing the purpose and application of Logit Link Functions in order to transform regression models to predict binary classes 

### Predicting College Admittance
- Using Linear Regression
  - Fitting model with Scikit-Learn's Linear Regression class
  - Predicting the binary indicator admit using GPA
  - Plotting predictions to examine the interpretability of coefficients/intercepts 
- Using Logistic Regression
  - Fitting model with Scikit-Learn's Logistic Regression class
  - Predicting the binary indicator admit using GPA
  - Plotting predictions to examine the interpretability of coefficients/intercepts 
  - Fitting model on centered predictor variables and examining admittance probabilities at various GPAs through instantiated logistic transformation function 
