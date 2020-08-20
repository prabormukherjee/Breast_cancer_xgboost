# Breast_cancer_xgboost

Based on certain feature predict whether a tumor is a cancer or not. To predict properly I used a lot of visualization technique to analyze the data. Original dataset has more than 30 feature. But a lot of features are correlated with each other. So I performed a lot of EDA steps and plot the features in hitmap to check their corelation. Finally I drop all col which has a strong co-relation with other. Our dataset has also class unbalence problem. That can be overcome by oversampling the minority class(smote) or undersampling the majority class.   
Finally I train 3 different model, using xgboost, recursive feature elimination with Cross-Validation and finally pca. It provided more than 97% acc.   
I added the dataset and source code here(python).
