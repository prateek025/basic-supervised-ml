# **Supervised ML in Python**

## I. Repository Overview

- This repository contains tutorials that cover building basic supervised machine learning models in python.
- Currently 1 tutorial notebook is available in this repository:
  1. `basic_ml_guide.ipynb` or `basic_ml_guide.pdf`
  
## II. Tutorial notebooks details

1. **`basic_ml_guide.ipynb` or `basic_ml_guide.pdf`**
    - This notebook covers developing and tuning basic classification and regression models in python.
    - Dataset used for analysis is [Sarah Gets a Diamond](http://store.darden.virginia.edu/sarah-gets-a-diamond) taken from University of Virginia, Darden Business Publishing.
    - The regression model predicts the price(Y variable) of a diamond based on its multiple physical attributes/features(X variables). For the classification model, I have changed the definition of the Y variable. For all diamonds with price greater than $10,000 High/H label was added and for the remaining Low/L label was added.
    - Basic data cleaning, data transformations, and pre-processing techniques have been applied on the on model development data. Model developement and Hyper-parameter tuning has been carried out for both the Regression and Classification models.
    - Since some of the plotly visualizations were not properly rendered on the python notebook they might not be visible on the notebool. I have added a `pdf` version of the python notebook where all the such visulaizations from python notebook were saved.
