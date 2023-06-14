# Telco Customer Churn Project Report

**Author:** Mehmet Reşit Çağan

## Introduction
In this project, we aimed to analyze telco customer churn data and build machine learning models to predict customer churn. This report summarizes the steps we took, the achievements, and the evaluation results of our models.

## Data Preprocessing
We performed several data preprocessing steps, including:
- Visualizing missing values to identify any data gaps.
- Dropping unnecessary columns that do not contribute to the churn prediction.
- Imputing missing values using appropriate strategies.
- Conducting data visualization to explore the relationship between churn and other attributes.

## Data Splitting and Preprocessing
To prepare the data for modeling, we split it into train and test sets. We also applied the following preprocessing techniques:
- Standardizing numeric attributes to ensure they have zero mean and unit variance.
- Performing one-hot encoding and label encoding to handle categorical variables.

## Model Evaluation
We evaluated several machine learning models using the test set and obtained the following accuracy scores:

| Model                        | Accuracy Score |
|------------------------------|----------------|
| Gradient Boosting Classifier | 0.8078         |
| Random Forest                | 0.8026         |
| AdaBoost Classifier          | 0.7936         |
| Logistic Regression          | 0.7823         |
| SVM                          | 0.7345         |
| Dummy Classifier             | 0.7345         |
| Decision Tree                | 0.7335         |
| KNN                          | 0.7113         |

From the evaluation, we observed that the Gradient Boosting Classifier achieved the highest accuracy score of 0.8078.

## Hyperparameter Tuning
To further improve the performance of the Gradient Boosting Classifier, we performed hyperparameter tuning using RandomizedSearchCV. Before tuning, the model achieved an accuracy score of 0.8078. After conducting the tuning process, we obtained an increased accuracy score of 0.8083. This improvement demonstrates the effectiveness of hyperparameter tuning in enhancing the performance of the model.

## Conclusion
In conclusion, we successfully analyzed the telco customer churn data and built machine learning models to predict churn. The Gradient Boosting Classifier showed the highest accuracy, and after hyperparameter tuning, the accuracy slightly improved. Our project highlights the importance of data preprocessing, model evaluation, and hyperparameter tuning in achieving accurate predictions for telco customer churn.

**Data Link:** [https://www.kaggle.com/blastchar/telco-customer-churn](https://www.kaggle.com/blastchar/telco-customer-churn)
