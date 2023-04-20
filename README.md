# House Loan Data Analysis
This project aims to analyze historical data of house loans and build a deep learning prediction model to predict the chance of default for future loans. The dataset used in this project is highly imbalanced and includes multiple features, making it a challenging problem in the domain of finance.

* Objective
The objective of this project is to create a deep learning model that can accurately predict whether an applicant will be able to repay a loan using historical data. The model will be trained on the dataset provided, and its performance will be evaluated using various metrics.

* Project Steps
The following steps were performed in this project:

* Load the dataset: The dataset provided was loaded into the programming environment using Python with the help of Pandas library.

* Check for null values: The dataset was checked for any missing or null values using the isnull() function in Pandas. Missing values, if any, were handled appropriately by either dropping the rows or columns or filling them with suitable values.

* Print percentage of default to payer: The percentage of default to payer in the TARGET column of the dataset was calculated using the value_counts() function in Pandas. This helped in understanding the class distribution and identifying if the data is imbalanced.

* Balance the dataset: As the dataset was found to be imbalanced, techniques like oversampling and undersampling were used to balance the data. The oversampling technique SMOTE (Synthetic Minority Over-sampling Technique) was applied to generate synthetic samples of the minority class.

* Plot the data: The balanced dataset was visualized using various plots like bar charts and histograms using Matplotlib library in Python. This helped in understanding the class distribution and identifying any patterns or trends in the data.

* Encode the columns: The categorical columns in the dataset were encoded into numerical values using label encoding and one-hot encoding techniques. This was done using libraries like Pandas and Scikit-learn in Python.

* Calculate Sensitivity: Sensitivity, a key metric in binary classification, was calculated using the formula TP / (TP + FN), where TP is the number of true positives and FN is the number of false negatives. This was done to evaluate the model's ability to correctly predict positive cases.

* Calculate area under ROC curve: The AUC-ROC (Area Under Receiver Operating Characteristics Curve) was calculated using the roc_auc_score() function in Scikit-learn. This metric was used to evaluate the overall performance of the model.

# Results
The deep learning model was successfully trained on the balanced dataset and evaluated using various metrics. The sensitivity, or recall, was found to be high, indicating that the model was able to correctly predict a large proportion of positive cases. The AUC-ROC value was also found to be satisfactory, suggesting that the model has good discriminatory power in distinguishing between positive and negative cases.

* Conclusion
In conclusion, this project demonstrates the process of analyzing historical data of house loans and building a deep learning prediction model for predicting the chance of default for future loans. The steps involved in data preprocessing, balancing the dataset, encoding categorical columns, and evaluating the model's performance using metrics like sensitivity and AUC-ROC were performed. The results obtained suggest that the developed model has the potential to effectively predict loan defaults and can be used as a tool for safe and secure lending decisions.

Usage
To run this project, follow these steps:

Install the required libraries: Pandas, Matplotlib, Scikit-learn, etc.
Load the dataset into your programming environment.
Run the code for data preprocessing, balancing the dataset, encoding columns, and building the deep learning model.
Evaluate the model
