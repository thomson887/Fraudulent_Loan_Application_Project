# Fraudulent_Loan_Application_Project
ML based project to correctly identify fraudulent loan applications.


Final Insights
Objective: I was asked to create a model which could correctly identify a fraudulent loan application.

Challenges:

One of the biggest challenges I faced was finding a real case dataset which prompted me to create a synthetic dataset.
The dataset could have been made better by introducing relationships between features such as credit score and bankruptcy history (credit score should be lower as the number of bankruptcy history goes up).
Normally distributed columns such as applicant_age, applicant_income etc wouldve introduced more correlation between the data.
Developing relationships between the features and the target feature 'fraudulent' would introduce more causality in the dataset and thus improve the model performance.
Model Performance: I selected Logistic regression, XGBoost Regressor, Light GBM, SVM and Naive Bayes model on this dataset. All of the models gave very poor Precision i.e. model predicted fraudulent cases were actually fraudulent. Few models such as SVM and Naive Bayes models provided better Recall as compared to the other models indicating that they were really good at identifying actual fraudulent cases.

Best model selection: Based on the results which I have seen on this dataset I believe a better dataset would provide very good results on SVM model as it was able to identify fraufdulent cases as fraudulent which is more important for the safety of the business. However in the long run incorrectly identifying a non-fraudulent application as a fraudulent loan application will result in lower profits.

Improvements:

Apart from a better dataset, techniques such as hyper-parameter tuning, data balancing technique, ensemble approaches could prove useful in getting better results in the classification models.
