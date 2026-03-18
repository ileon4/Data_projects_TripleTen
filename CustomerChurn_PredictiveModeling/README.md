## Customer Churn Predictive Modeling Project

This project analyzes customer churn for Beta Bank by building machine learning models to predict which customers are likely to leave the bank, helping the bank retain existing customers rather than acquiring new ones.

----------

Several Beta Bank customers are leaving every month. The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones.

With my modeling, I predict whether a customer will leave the bank soon. I use the data on clients’ past behavior and termination of contracts with the bank.

----------

Tools: Python - scikit-learn

### Measurable Success:
☆ Achieved 61.18% **F1 score** on test set, exceeding the 59% target requirement  
☆ Trained and compared 2 different algorithms (**Logistic Regression**, **Random Forest**)
☆ Performed systematic hyperparameter tuning across 20 parameter combinations
☆ Addressed severe class imbalance (79.6% vs 20.4% distribution) using 4 different techniques
☆ Achieved 84% overall **accuracy** with 62% **precision** and 60% **recall** for churn prediction
☆ Generated **AUC-ROC score** of 0.58, demonstrating model's discriminative ability
☆ Correctly identified 223 out of 371 churning customers (60% recall) while maintaining precision
☆ Reduced false negatives from 371 (baseline) to 148 (final model), improving churn detection by 60%

## Images of Features

### Feature Encoding
<img width="770" height="503" alt="image" src="https://github.com/user-attachments/assets/8500a445-5490-42e1-8afe-d8b5fc8617b4" />

### Upsampling and Downsampling to Address Class Imbalance
<img width="772" height="505" alt="image" src="https://github.com/user-attachments/assets/9c8c5ba2-5669-4167-be32-c34087ac1b4f" />
<img width="757" height="569" alt="image" src="https://github.com/user-attachments/assets/b2b4d267-c7e7-461c-93d1-4b3d8dcd0c0e" />

### RandomForestClassifier Model with Hyperparameter Optimization
<img width="729" height="709" alt="image" src="https://github.com/user-attachments/assets/ec5996e2-2f68-48ec-a1f2-68790cf3d6ed" />

### ROC & AUC-ROC
<img width="426" height="527" alt="image" src="https://github.com/user-attachments/assets/a8b7e97e-132f-4784-bd1a-b02dcde79e70" />

### Testing Final Model
<img width="422" height="546" alt="image" src="https://github.com/user-attachments/assets/630e991c-f30e-41e7-875f-562a178f627c" />

