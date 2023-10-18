# CHL5230FinalProject
## Authors: Feifan Xiang, Yutong Lu, Xiaoxuan Han


**Use diabetes data set**


## Research Question
- What are the factors associated with diabetes?
- What is the minimum change in biomarkers to enter another class?
- What are the differences in the risk of developing diabetes between patients who are diagnosed with depression and who are not? 


## Steps
- Data cleaning
  - Deal with missing data using imputation methods;
- Data engineering 
  - Conduct dimension reduction to select the most appropriate relevant features;
  - Perform correlation heatmaps to explore potential associations among features; 
  - Feature selection: correlation, feature importance, clinical implications (referring to 10+ studies);
  - Normalization
- Modeling
  -  Logistic regression (0/1 diabetes);
  -  Naive bayes (Gussian Naive bayes, Bernoulli NB, if imbalanced Complement NB);
  - KNN;
  -  Clustering (unsupervised)
-  Modeling evaluation (cross validation)
-  Results
    -  dentify and interpret crucial features that are associated with diabetes;
    -  See what the minimum change in the biomarkers will flip the patients into another class;
-  Implications
    -  Provide preventive measures for diabetes;
    -  Offer insights into identifying biomarkers that lead to change in class 


## Possible challenges
-  How do we deal with the potential correlations between rows because one patient may appear in different rows?
-  If we have imbalanced classes, we might need to do upsampling.
-  How to deal with depression in the dataset (possible subset)?


