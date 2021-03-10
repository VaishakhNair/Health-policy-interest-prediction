# Health-policy-interest-prediction

(P.S Github sometimes takes time while loading ipynb files, so just reload a couple times if it shows you error. or you can render it using https://nbviewer.jupyter.org/. Open the link and just copy paste the link of ipynb file. It should display just fine then :) )

A binary prediction model for health policy interest prediction

PROBLEM : Build a binary prediction model that allows us to predict the likelihood of customer buying a health policy.

APPROACH : After observing the dataset initially, it was understood that the target variable is "Response". The target variable has two values '0' or '1'. This helped understand that the above problem can be solved by Supervised Learning Classification Approach.


Roadmap followed for the problem :
1) EXPLORATORY DATA ANALYSIS : Analysing the dataset and trying to understand the values, what they represent etc.
2) FEATURE ENGINEERING : This stage involves converting the values in the dataset into the type which can be easily interpreted by the ML model.
3) FEATURE SELECTION : Deciding on which features should be fed to the model and which should be dropped.
4) MODEL CREATION : Model was created using a hyperparameter tuned CatBoostClassifier 
