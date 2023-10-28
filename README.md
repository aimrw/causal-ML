# causal-ML
Final project for Causality with Machine Learning Course. Group Project with Jingci Zhu.

We conduct a difference-in-differences analysis to determine the effect of VAT tax reform on firms’ level of investment towards the fixed assets, machinery, and equipment. We estimate the effect of 2004 and 2007 reforms using the double machine learning estimator. We check for parallel trends and overlap assumptions. We use machine learning to estimate the conditional expected outcome and propensity score. We try linear/logistic regression, gradient boosting, and random forests, and run 5-fold cross validation, selecting the model with the lowest MSE or cross entropy. We plug in these estimates into the AIPW estimator and find that no significant effect on investment in the 2004, but a significant positive effect on investment in 2007.
