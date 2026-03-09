## Project overview

This project uses the Home Credit Kaggle data base. Home Credit is a financial services company that provides loans to customers often underserved by traditional banking institutions. The goal is to use machine learning to assess the risk of default at the loan application stage, enabling better decision-making and optimized loan offerings. Understanding which customers are likely to default is crucial for reducing financial losses and improving operational efficiency.

## Objective

To build a predictive model that estimates the probability of default at the loan application stage.

## Methods

- Data preprocessing
- Feature engineering
- Machine learning classification models
- Model evaluation

## Dataset

Home Credit Default Risk dataset (Kaggle)

## Tools

Python  
Pandas  
Scikit-learn  
Jupyter Notebook

## Results 

The best model is determined as predicting non-defaults best. As the worst case scenario for this project will be incorrectly predicting a non-default the loss of wrongly predicting a non-default is disporportionally large compared to the gains of interests.

The Best model is tied between CatBoost and LightBoost, as they have the best precision while predicting Non Defaults (0.91). While other models stayed close behind like the LR. Compared to other implemented models in terms of metrics such as recal, f-1score and accuracy CatBoost comes out on top, with it's limitations. CatBoost can be resource-intensive and difficult to interpret for non-technical stakeholders. It also relies on clean, high-quality data.
