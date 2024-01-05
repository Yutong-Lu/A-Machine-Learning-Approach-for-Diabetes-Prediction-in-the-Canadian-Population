# A Machine Learning Approach for Diabetes Prediction in the Canadian Population
## CHL5230FinalProject
## Authors: Feifan Xiang, Yutong Lu, Xiaoxuan Han

**The final code are Updated_FINAL.ipynb and NLP_cleaning_and_word_cloud.ipynb**

## Introduction
- Investigates diverse risk factors associated with diabetes in the Canadian population using data from the Canadian Primary Care Sentinel Surveillance Network (CPCSSN).
- Aims to improve diabetes monitoring and prevention by modeling diabetes separately by depression status.

## Methods
- Utilizes a Diabetes Study dataset of 10,000 observations in 2017, containing patient visit records with various demographic, clinical, and medical history features.
- Uses machine learning models including XGBoost, K-nearest neighbor (KNN), logistic regression, random forest, Naive Bayes, Linear Discriminant Analysis (LDA), Quadratic Discriminant Analysis (QDA), and a recurrent neural network with long short-term memory (RNN-LSTM).
- Normalizes data, handles missing values, and performs feature selection and hyperparameter tuning for model optimization.

## Results
- XGBoost model exhibits the best performance overall, achieving high recall, precision, and accuracy in identifying diabetic patients.
- XGBoost models perform well in predicting diabetes status regardless of depression status, showcasing consistency across different patient groups.
- RNN-LSTM model for patients with multiple records achieves high accuracy in diabetes prediction.

## Discussion
- Highlights the importance of predicting diabetes for early intervention and lifestyle changes.
- Identifies gaps in ML research regarding health disparities and ethical biases, particularly in addressing diversities in healthcare outcomes.

## Limitations and Future Work
- Acknowledges limitations in the dataset and model interpretability.
- Suggests including additional patient features and exploring different modeling techniques for further research.

## Resources, Data Source and References
- Data sourced from CPCSSN (not public).
- [Presentation slides available](https://docs.google.com/presentation/d/1kudnKw8dffWUwt7Feq0L6tPMxecSO5JkQK6iUzEz49k/edit#slide=id.g2a136b5ce98_0_4)
- References cited in the report cover various aspects of diabetes prediction and machine learning in healthcare.
- For more details, refer to the full report and associated resources provided in the GitHub repository.
