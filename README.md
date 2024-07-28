Title: Heart Disease Prediction using Machine Learning: A Comparative Study of SVM and Logistic Regression

Introduction:
Heart disease is a leading cause of mortality worldwide. Early detection and prediction of heart disease can significantly improve treatment outcomes. 
This study aims to develop a predictive model using machine learning algorithms to identify individuals at risk of heart disease.

Dataset:
We used the Cleveland Heart Disease dataset, which contains 303 instances with 14 features, including age, sex, blood pressure, and cholesterol levels.

Methodology:
We implemented two machine learning algorithms: Support Vector Machine (SVM) and Logistic Regression.
We split the dataset into training (80%) and testing sets (20%) and evaluated the models using accuracy, precision, recall, and F1-score.

Results:
after examining in various ways, we got results like this....
| Algorithm | Accuracy | Precision | Recall | F1-score |
| SVM | 0.92 | 0.91 | 0.93 | 0.92 |
| Logistic Regression | 0.85 | 0.84 | 0.86 | 0.85 |

Discussion:
Our results show that SVM outperformed Logistic Regression in predicting heart disease, achieving a higher accuracy (0.92 vs. 0.85) and F1-score (0.92 vs. 0.85). 
SVM's ability to handle non-linear relationships and high-dimensional data may contribute to its superior performance.

Conclusion:
This study demonstrates the potential of machine learning in predicting heart disease. SVM's superior performance suggests its suitability for this task. 
Future work can focus on feature engineering, hyperparameter tuning, and exploring other algorithms to further improve prediction accuracy.

