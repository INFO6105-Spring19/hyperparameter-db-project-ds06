
AI Skunkworks Project - Hyperparameters Database

Goals and Objectives :
In statistics, hyperparameter is a parameter from a prior distribution; it captures the prior belief before data is observed. In any machine learning algorithms, these parameters need to be initialized before training amodel. H\We would create H2O models for this dataset for getting proper hyperparameters. Background Research: Hyperparameters are variables that we need to set before applying a learning algorithm to a dataset. In machine learning scenarios, a significant part of model performance depends on the hyperparameter values selected. The goal of hyperparameter exploration is to search across various hyperparameter configurations to find the one that results in the optimal performance. The challenge with hyperparameters is that there are no magic number that works everywhere. The best numbers depend on each task and each dataset. The hyperparameter database to be developed as a part of this project is an open resource with algorithms, tools, and data that allows users to visualize and understand how to choose hyperparameters that maximize the predictive power of their models. Phase I of the project involves selecting a unique dataset containing predicted target variables, hyperparameters, meta-data etc. by running different models (with varying hyperparameters) on it using H2O.

We have used large set of data of house price prediction

Find a dataset
Figure out the algorithms that will work for that dataset. The type of algorithm like classification or Regression algorithm. Perform H2O in python for generating various models at various runtime. Suppose hypothetically if five algorithms are used then the best models for those algorithms will be selected to get the hyperparameter.

Implementing H2O analysis.
Getting optimized hyperparameters. The model might overfit for the training dataset which will not work well on the test dataset. Other challenge would be to tune model and feature parameters well.