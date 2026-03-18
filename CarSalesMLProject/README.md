## Car Sales Machine Learning Project

This project compares different machine learning models used to best predict car prices for a car sales company wanting to building an app. The first portion of the project is dedicated to properly encoding features and then I go on to train and test 6 different models.

----------

Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value. 

Rusty Bargain is interested in:

- the quality of the prediction
- the speed of the prediction
- the time required for training

----------

Tools: Python - scikit-learn
Models Used: Linear Regression, Decision Tree, Random Forest, LightGBM, CatBoost, XGBoost

### Measurable Success:

☆ Trained and systematically compared 6 different algorithms (Linear Regression, Decision Tree, Random Forest, LightGBM, CatBoost, XGBoost)  
☆ Performed comprehensive hyperparameter tuning across 27 parameter combinations for gradient boosting models  
☆ Implemented target encoding for high-cardinality features (Brand: 40 categories, Model: 250 categories)  
☆ Created one-hot encoding for 3 categorical features, expanding to 32 final features  
☆ Engineered ordinal encoding for datetime features using business-relevant time buckets  
☆ Achieved 1,740.73 RMSE on validation set with LightGBM, significantly outperforming baseline Linear Regression by 45.6% (3,193.60 vs 1,740.73)  
☆ Delivered 1,780.93 RMSE on final test set, meeting production-quality prediction standards  
☆ Achieved 84.48% R² score on test set, explaining majority of price variance  
☆ Maintained 1,096.20 MAE (Mean Absolute Error), indicating robust prediction accuracy


## Images of Features

### Datetime Feature Encoding with Custom Function
<img width="1438" height="1260" alt="image" src="https://github.com/user-attachments/assets/a7432aff-8459-4d6e-ad83-e500ec0ac28f" />

### Declaring Feature Variables and Splitting the Data
<img width="1440" height="544" alt="image" src="https://github.com/user-attachments/assets/616a1a26-7036-44ae-bf7a-48670bd59fc3" />

### Target Encoding for High Cardinality Features
<img width="719" height="489" alt="image" src="https://github.com/user-attachments/assets/57aca9b6-4171-4400-8dc7-f0e27fa27334" />

### LightGBM Training with Hyperparameter Optimization
<img width="1280" height="1276" alt="image" src="https://github.com/user-attachments/assets/83296dc3-899d-467a-ac19-ad1d4795c2f2" />

### Testing Final Model with RMSE, MAE, and R2 Metrics
<img width="1276" height="568" alt="image" src="https://github.com/user-attachments/assets/0a3f82d5-65d6-4b6a-a891-ca93115d0699" />

