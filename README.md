# DSC-420-Kaggle-Playground-Project
**Project Overview**
This project focuses on predicting airline passenger satisfaction using the Kaggle Playground Series dataset. We compared several classification models to determine which approach produced the strongest predictions, using ROC AUC as our main evaluation metric.

**Methods**
We started by exploring the data to see how different factors, including service ratings, flight delays, and travel class, related to passenger satisfaction. After handling missing values and preparing the predictors, we tested logistic regression, random forests, and boosting methods to compare their performance. We also tested combining LightGBM and histogram gradient boosting predictions to see whether blending the models improved our AUC score.

**Results**
Our final Kaggle submission received a score of 0.95932. We used cross-validation to compare our models and determine which approach worked best before making our final submission.
