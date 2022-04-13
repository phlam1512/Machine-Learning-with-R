# Machine Learning with R
Data analysis using machine learning methods implemented in R and using the `tidymodels` package.

## Aim
The aim is to analyse and present findings on a dataset with machine learning methods implemented in R (in particular using the `tidymodels` package). The focus is to model the relationship between the response variable and a set of predictors.

## Specification
This project uses multiple machine learning models or methods, with the following requirements. Note that it is allowed to use one model to meet multiple requirements.
- At least one model must be simple enough to consider as a baseline for comparison to the more sophisticated models. Regression models or nearest neighbors methods, based on only a few predictors, are good candidates for baseline methods.
- At least one model should be fit using your own implementation of gradient descent. The only restrictions on this model are that the gradient of the loss function should not be a constant. You are free to use a simple model and a simple loss function to make the derivation and computation manageable.
- At least one *non-baseline* model must be (relatively) interpretable. For this model you should write a brief sub-section including your interpretation of the results. You could compare to a baseline model on both predictive accuracy and (in)consistency of interpretations.
- At least one model must be (relatively) high-dimensional. If your dataset has many predictors, and the number of observations is not much larger, then for example you could fit a penalized regression model using all the predictors. If your dataset does not have many predictors you could consider models that include non-linear transformations, interaction terms, and/or local smoothing to increase the effective degrees of freedom.
- At least one model must be (relatively) more focused on predictive accuracy without interpretability. Imagine that you would submit this model to a prediction competition where the winner is chosen using a separate set of test data from the same data generating process (in-distribution generalization).

## Remarks
This group project is submitted as part of assessed coursework for a module at LSE: ST310 Machine Learning.

## Files
- `main.Rmd` contains all R code and analysis.
- `main.html` is the knitted version of `main.Rmd`. A live HTML version can be viewed directly here: http://htmlpreview.github.io/?https://github.com/phlam1512/Machine-Learning-with-R/blob/main/main.html.
- `dataset.csv` is the dataset analysed. Originally sourced from *Kaggle*: https://www.kaggle.com/datasets/blastchar/telco-customer-churn.
