Customer Churn Prediction Using Machine Learning

Project Overview

This project focuses on analysing customer churn and using machine learning to predict whether a customer is likely to leave a service.

I worked with a telecommunications customer dataset and followed a complete data science workflow, starting with data cleaning and exploratory analysis and then moving into machine learning and model evaluation.

Aim

The main aim of this project is to understand customer churn patterns and build classification models that can help predict customer churn.

Objectives

* Clean and prepare the customer dataset.
* Explore patterns related to customer churn.
* Visualise important customer characteristics.
* Convert categorical data into a format suitable for machine learning.
* Train different classification models.
* Compare model performance.
* Identify important features used by the model.
* Present practical business recommendations.

Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains information about customers, including:

* Customer tenure
* Contract type
* Monthly charges
* Total charges
* Internet services
* Payment methods
* Customer churn status

The original dataset contains 7,043 customer records and 21 columns.

Data Preparation

The following preprocessing steps were carried out:

1. Inspected the dataset and its data types.
2. Checked for missing values.
3. Converted TotalCharges into a numeric format.
4. Removed records with invalid/missing TotalCharges.
5. Checked for duplicate records.
6. Removed the customerID identifier.
7. Converted the Churn target into binary values.
8. Applied one-hot encoding to categorical variables.
9. Split the data into training and testing sets using an 80/20 split.

Exploratory Data Analysis

I explored several factors that may be useful for understanding customer churn.

Customer Churn Distribution

The churn distribution shows the number of customers who stayed with the service compared with those who left.

Customer Churn by Contract Type

Contract type was compared with churn status. The analysis showed different churn patterns across month-to-month, one-year and two-year contracts.

Monthly Charges and Churn

Monthly charges were compared between customers who churned and customers who stayed.

Customer Tenure and Churn

Customer tenure was analysed to understand how the length of the customer relationship relates to churn patterns.

All project visualisations are available in the figures folder.

Machine Learning Models

I trained and compared three classification models:

* Logistic Regression
* Decision Tree
* Random Forest

The models were trained using the prepared customer dataset and evaluated on the test data.

Model Evaluation

The project uses several evaluation methods, including:

* Accuracy
* Classification report
* Confusion matrix
* ROC-AUC
* Random Forest feature importance

The exact model results are available in the Google Colab notebook included in this repository.

Key Findings

Some important patterns identified during the analysis include:

* Customer churn represents a smaller but important part of the customer population.
* Contract type shows noticeable differences in churn patterns.
* Monthly charges differ between customers who churn and those who remain.
* Customer tenure provides useful information for predicting churn.
* Machine learning can combine multiple customer characteristics to make churn predictions.
* Random Forest feature importance helps identify which variables the model relies on most.

Business Recommendations

Based on the analysis, businesses could:

* Pay closer attention to customers in the early stages of their relationship.
* Consider targeted retention strategies for customers on shorter contracts.
* Review pricing and service options for customers with higher monthly charges.
* Use predictive models to identify customers who may need additional support.
* Combine machine learning predictions with customer service knowledge before making retention decisions.

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* GitHub

Project Structure

customer-churn-prediction/
│
├── README.md
├── customer_churn_prediction.ipynb
├── cleaned_customer_churn.csv
│
└── figures/
    ├── churn_distribution.png
    ├── contract_vs_churn.png
    ├── monthly_charges.png
    ├── customer_tenure_distribution.png
    ├── random_forest_confusion_matrix.png
    ├── top_10_features.png
    └── model_accuracy_comparison.png

What I Learned

Through this project, I gained practical experience in preparing real-world data, performing exploratory analysis, creating visualisations, preparing features for machine learning and comparing classification models.

It also helped me understand the importance of presenting machine learning results clearly rather than focusing only on model performance.

Author

Palle Sai Supritha

MSc Data Science
University of Hertfordshire

⸻

This project was created as a practical Data Science portfolio project
