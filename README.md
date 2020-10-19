# Supervised Learning : Challenge 17

During this analysis, I utilized three different techniques to address class imbalance. Those being the Combination Approach, Oversampling and Undersampling. This allowed me to effectively asses the "loan risk".
## Technique: Oversampling 
Oversample the data using the RandomOverSampler and SMOTE algorithms.
### Results 
##### Oversampling Results:

The average of recall using the oversampling model produce a balanced accuracy score of 0.63. This proves the model is very weak for this analysis due its low score. 
F1 Scores:
High Risk - 0.02
Lower Rosk - 0.81


SMOTE oversampling Results: 
###### * SMOTE oversampling is a method of synthesizing additional sample data from existing data, which is an alternative to oversampling from the actual data set. 

Believe it or not the SMOTE model was not effective either. In fact, the outcome was weaker than the oversampling technique and gave balanced accuracy score of only 0.604.
F1 SCores:
High Risk - 0.02
Low Risk - 0.78
