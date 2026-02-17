# Title: Credit Card Fraud Detection using Sampling Techniques

## 1. Methodology

The Creditcard_data.csv dataset is used in this project to detect fraud. Various sampling techniques are used to balance the dataset because it is extremely unbalanced (fraud cases are very few compared to non-fraud cases).
Five distinct machine learning models are used to train the dataset after it has been balanced. The optimal sampling strategy is determined for each model after the accuracy of each model is computed for each sampling technique.

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

This project is about fixing the problem of class imbalance in machine learning. Fraud detection datasets have very few fraudulent transactions, which makes models more likely to predict non-fraud transactions.
Resampling methods, such as oversampling and undersampling, are used to fix this. The project looks at the results of different sampling methods and figures out which one works best for different ML models.      

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

Best Techniques (from output):

M1 (Logistic Regression): Sampling5

M2 (Decision Tree): Sampling2

M3 (Random Forest): Sampling2

M4 (SVM): Sampling5

M5 (Naive Bayes): Sampling5

Overall, Sampling5 outperformed the rest, as it gave the best accuracy for the maximum number of models.
