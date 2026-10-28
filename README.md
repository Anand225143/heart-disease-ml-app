# Heart Disease Classification and Streamlit Deployment

## a. Problem statement
The objective of this project is to build and evaluate multiple machine learning classification models to predict the presence of heart disease in patients based on clinical attributes.

## b. Dataset description
- **Source:** UCI Machine Learning / Kaggle Heart Disease Dataset
- **Number of Instances:** 1,000 (Satisfies requirement of >= 500)
- **Number of Features:** 13 clinical attributes (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal).
- **Target Variable:** target (0 = No Heart Disease, 1 = Heart Disease Present).

## c. Github Repository Link
https://github.com/your-username/heart-disease-ml-app

## d. Models used & Performance Comparison

| ML Model Name | Accuracy | AUC | Precision | Recall | F1 | MCC |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| Logistic Regression | 0.7250 | 0.7800 | 0.7227 | 0.7963 | 0.7577 | 0.4443 |
| Decision Tree | 0.6000 | 0.5966 | 0.6273 | 0.6389 | 0.6330 | 0.1936 |
| KNN | 0.5850 | 0.6204 | 0.6050 | 0.6667 | 0.6344 | 0.1582 |
| Naive Bayes | 0.7150 | 0.7690 | 0.7179 | 0.7778 | 0.7467 | 0.4239 |
| Support Vector Machine | 0.6950 | 0.7400 | 0.6850 | 0.8056 | 0.7404 | 0.3838 |

### Observations on Model Performance

| ML Model Name | Observation about model performance |
| :--- | :--- |
| **Logistic Regression** | Achieved the highest overall accuracy (72.5%) and AUC (0.7800), handling linear relationships effectively. |
| **Decision Tree** | Lower generalization performance (Accuracy: 60.0%), likely due to minor overfitting on training splits. |
| **KNN** | Moderate performance (Accuracy: 58.5%), sensitive to feature scaling and neighborhood distance calculations. |
| **Naive Bayes** | Strong performance (Accuracy: 71.5%), benefiting from feature independence assumptions across medical markers. |
| **Support Vector Machine** | Achieved the highest recall (80.56%), effectively minimizing false negatives with an overall accuracy of 69.5%. |
| **Overall, Winner for your dataset?** | **Logistic Regression** (Highest Accuracy, AUC, and MCC score). |
