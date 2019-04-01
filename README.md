# sales_prediction
Data from https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data

Summary:
1. EDA.py: 
explored missing values and some patterns. Analysis is contained in the notebook

2. preprocess_data.py:
data engineering: generated all shop-item pairs due to a monthly prediction, mean encoding, and lag features

3. randomforest.py:
created a model with the method of random forest regression

4. LightGBM.py:
created a model with the method of LightGBM 

5.ensemble.py:
stacked two models with the method of linear regression


Results:
1. Random Forest RMSE:1.24
2. LightGBM RMSE:0.92
3. Stacking RMSE:0.91
4. RMSE of stacking using linear regressison is slightly lower than that of lightgbm.so stacking method outperforms other two methods.

