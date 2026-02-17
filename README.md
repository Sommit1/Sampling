# Title: Credit Card Fraud Detection using Sampling Techniques

## 1. Methodology

In this project, the dataset Creditcard_data.csv is used for fraud detection. Since the dataset is highly imbalanced (fraud cases are very less compared to non-fraud cases), different sampling techniques are applied to balance the dataset.
After balancing, the dataset is trained using 5 different machine learning models. The accuracy of each model is calculated for every sampling technique and the best sampling method is identified for each model.

### Sampling techniques used:

 - Random Under Sampling

 - Random Over Sampling

 - SMOTE

 - NearMiss

 - Tomek Links

### Models used:

 - Logistic Regression
 
 - Decision Tree

 - Random Forest

 - SVM

 - Naive Bayes

## 2. Description

This project focuses on solving the class imbalance problem in machine learning. In fraud detection datasets, the number of fraudulent transactions is very low, which makes models biased toward predicting non-fraud transactions.
To solve this, resampling techniques (oversampling and undersampling) are applied. The project compares results of multiple sampling techniques and determines which technique gives best performance for different ML models.   

## 3. Input / Output

### Input

Dataset file: Creditcard_data.csv

Features: Transaction-related columns

Target column: Class



### Output

Accuracy table for each model with each sampling technique

<img width="583" height="246" alt="image" src="https://github.com/user-attachments/assets/a96e0534-a86e-433c-a6c6-7db99bc36090" />


Best sampling technique for each model

<img width="466" height="238" alt="image" src="https://github.com/user-attachments/assets/ec5e8dd1-3307-419d-ace5-0b04508f7cef" />


Overall best model + sampling combination

<img width="746" height="156" alt="image" src="https://github.com/user-attachments/assets/4d1ad368-da1e-4f66-9114-6b59f0cbd2fa" />


### 4. Conclusion

From the results, sampling techniques clearly improved model performance on the imbalanced credit card dataset.
Sampling5 performed best for most models (M1, M4, M5) and achieved the highest accuracy of 98.62% (M1) and 98.71% (M4).
Sampling2 outperformed others for M2 and M3, giving 97.67% (M2) and 98.71% (M3).

Overall, Sampling5 outperformed the rest, as it gave the best accuracy for the maximum number of models.
